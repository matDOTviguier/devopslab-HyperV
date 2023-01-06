# devopslab-HyperV
Another devopslab under HyperV

**1. Prepare hosts**

Hosts are based on minimal debian stable amd64 dvd images with a single aio 16G ext4, with no software installed.

![Capture d’écran 2023-01-06 143853](https://user-images.githubusercontent.com/2384485/211023467-88f2619b-6968-45c9-a3a8-5bd1604550b2.png)

Once connected, edit your `etc/apt/sources.list` file in order to remove the CDROM line and then, install **curl** (in order to download scripts) and **ssh** (in order ... *well, you should kown why*).

`apt -y update`

`apt -y upgrade`

`apt -y install ssh curl`  

