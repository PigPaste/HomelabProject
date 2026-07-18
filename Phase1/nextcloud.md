<h1>Nextcloud Installation</h1>

Now that the Raspberry Pi is completely configured, we can start to install Nextcloud.

First, you need to install a service called "Snap", which will allow you to directly install Nextcloud. You can install Snap by using the following command:

sudo apt install snapd -y

Next, you can install Nextcloud with this command (This might take longer than the previous command):

sudo snap install nextcloud

And after that command is done running, you can double check that it installed correctly by running this command:

sudo snap services

Which should display text like this:

<img width="663" height="191" alt="Screenshot_20260718_011429" src="https://github.com/user-attachments/assets/3857ff69-f4ac-415c-8652-e4169ad04c7a" />
