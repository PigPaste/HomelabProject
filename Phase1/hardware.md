<h1>Hardware</h1>

| Component     | Specification                 | 
| ------------- | ------------------------------|
| Raspberry Pi  | Raspberry Pi 5 (8GB)          |
| Storage       | [1 TB NVMe SSD](https://www.amazon.com/BIWIN-NV7400-Gen4x4-Internal-Desktop/dp/B0DM1R7KHZ?crid=238JIVYTHP351&dib=eyJ2IjoiMSJ9.oMEOR6Qwn8YJUjvTk_wjD_JUBfUhvZ4pqgZyCRDNZ86C4XeHM43cVH6BFUKYcaYA9ccST7k-wirWl4pDNe7cvVOcGlL1f3o3cFfHYe3_dP--U9O8ABXz8P_vIqo_SvwmNEvRqVjq7ltsCShveACu-s-C2v5MDnetbiPpllblHTkXWRIQ8_hztRVBbB2k3ZehJwXUI5QTqmPWg-0LAGVqVdMF45WNpxn3kpx0CYFafdk.oyqA_6JTbWhMVj3qnJGu5zbiDQnWHqRmw9V36PINRRc&dib_tag=se&keywords=1+tb+nvme+ssd+BIWIN+black+opal&qid=1784152296&sprefix=1+tb+nvme+ssd+biwin+black+o%2Caps%2C317&sr=8-3)                 |
| SSD Adapter   | [PCIe SSD HAT](https://www.amazon.com/Geekworm-X1001-Key-M-Peripheral-Raspberry/dp/B0CPPGGDQT?crid=2HTUC24M4QL3O&dib=eyJ2IjoiMSJ9.3pKHBhiakxY2zbM60L8zZgTqQJRMNf2fL1TaGuDUyt4SHdXjhZGMDL_BLJbCTxkwPY8n3ji8NSkYhgSRzuVTGwxG2yic5lvLt9Xaf9218AgLBZoMghGX43BPqHkun7YI787W_tQgmxo2ANPM_YSq0ARbnSz2S2Pm1kMjg4bkQMQpmRtchqUP0IjdRXkT1I0WtzDajceUFB7gBLjeGQKfRRgZa5W2ET533iWa3Ubg3OI.kCTsWhLncXteEGyC73cAxTbTRnVAkzHSMk5YTlGdv_Y&dib_tag=se&keywords=geekworm+x1001+pcie+to+m.2+hat&qid=1784152339&sprefix=geekworm+x1001+pcie%2Caps%2C344&sr=8-1)                  |
| Cooling       | [Active Cooling Fan](https://www.amazon.com/Raspberry-Aluminium-Temperature-Controlled-Accelerate-Dissipation/dp/B0CZLPX2HC?crid=1UZJFFB73LQK8&dib=eyJ2IjoiMSJ9.L6bhZG8m0KfFrIqEXVxrwoV8vxnwdUdM7jU8E-0O2iyLtLTijHB6yx1Gwf-4yYfxP37qnHka9jsVW8Hn1xwSyq0kBBgkBqc4_rROhCW15ZHvB0OixhYLt5w3afYCdukT60dkrWI4pB1S3qWQgZIKug2h8Z018ZP-Gaun0KSDMhrphGfFSGKrpmssULOEhHybP7McaIS9P9WEabXQEnvorXVlOAs7alrg6oQqPnPxJik.0y9QwE6AJZYqjr5YXVkMsIoEvZ-vdCfvmP0NX0U-hhg&dib_tag=se&keywords=Cooling+fan+for+pi5&qid=1784152675&sprefix=cooling+fan+for+pi5%2Caps%2C783&sr=8-3)            |
| Case          | [Geekworm P579 PCIe Metal Case](https://www.amazon.com/Geekworm-P579-V2-Raspberry-Support-Active/dp/B0CRD7XQCK?crid=1F2OC9LUXPHSO&dib=eyJ2IjoiMSJ9.1mes9HIIR0Njy29W61EpvE70V1rHARwf1Zx_JB_e_3ruzFtzh54QiA8_mebUWGLRQa1n2m8hwAUFszIxhlAAJWQJZ2vZpRev2DK2L_aQ_DGTGw5XY4tOEvIiwhSHqevNkwMsMfwjII1VGaIeJWcK55WCWTOr-tnU9TojmuuhPw06qZnqnZZCiOS-2RzYMF2U6luXuDFRpl-LdIrnwhvq5XJ23kkEeNAz4mS2IU7KAb4.s3-rP8O8g-vpBnRGH6coh5wEzW4pS_jpx84qhPWXc3A&dib_tag=se&keywords=geekworm+p579&qid=1784152210&sprefix=geekworm+p57%2Caps%2C379&sr=8-1) |

<h1>Hardware Assembly</h1>

<h2>Initial Fan Installation</h2>

First, remove the Raspberry Pi 5 from the box, and set it down

<img width="500" height="500" alt="45d159733_23550-raspberry-pi-5-4g-feature_x-2452663756" src="https://github.com/user-attachments/assets/c63b82ea-5d04-4eee-93b7-d129876495fb" />

Next, pull out the Aluminum Active Cooling Fan, and flip it over to see the thermal pads attached on the underside

<img width="512" height="226.5" alt="raspberry-pi-5-active-cooler-underside" src="https://github.com/user-attachments/assets/5fb4aad6-b110-42f0-8761-0b53ffe592a4" />

Peel off the plastic film on the underside of the fan and place it on top of the board, ensuring that the thermal pads are resting on their designated chips.

Afterwards, push the two push tabs into their respective slots on the board and plug the fan in, into the outlet on the board marked "fan", inbetween the USB-A sockets and the GPIO pin header near one of the push tab.

<img width="512" height="384" alt="raspberry-pi-5-active-cooler-installed" src="https://github.com/user-attachments/assets/4e5f8e78-de39-436c-b07c-635c17f09783" />

<h2>PCIe HAT Installation</h2>

<img width="700" height="700" alt="81LFCc8FnwL _AC_SL1500_" src="https://github.com/user-attachments/assets/d050a54e-569f-4e95-b7a4-d7cb7427026f" />

<h2>Geekworm P579 Metal Case Installation</h2>

<img width="700" height="700" alt="1400px-Installation_Guide-P579+X1001" src="https://github.com/user-attachments/assets/e24e7a41-f73f-45bd-9183-c6096caaba37" />

<h2>Final Product</h2>

<img width="384" height="512" alt="IMG20260708180805_Original" src="https://github.com/user-attachments/assets/baa6f432-49cb-4f27-a11d-adba52c3424f" /> <img width="375" height="500" alt="IMG20260710131346_Original_Original" src="https://github.com/user-attachments/assets/3e9e9bbc-52d2-4f5f-8917-7fb0427b660f" />


