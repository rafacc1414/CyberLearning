# Configuring a static IP address

## Linux

Find your network configuration

```bash
ifconfig
```

### First Option

You should see something similar to

<img src=".\images\ifconfig.JPG">

Identify your interface, in our case would be **"enp0s3"** and create a file if it is not already created as the following one.

```bash
sudo nano /etc/network/interfaces
```

Inside, put:

<img src="./images/static_ip_configuration.JPG">

Now, every time ubuntu boots up, it will catch the ip address 172.16.2.2

### Second Option

<img src="./images/NetworkManager.jpg">

## Kali-linux

Right click in the red square of the top of the image and then as do the image.

<img src="./images/NetworkManager_kali_linux.jpg">
