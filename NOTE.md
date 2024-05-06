## Fix WIFI adapter problem in Jetpack 6.3.0

https://forums.developer.nvidia.com/t/cant-access-wifi-on-jetson-orin-nano-running-jetpack-6-dev/278835

Try to install backport-iwlwifi-dkms and reboot jetson

> sudo apt install backport-iwlwifi-dkms