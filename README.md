# ubuntu-tweak

## disable upgrade

```
sudo apt remove unattended-upgrades
sudo apt remove unattended-upgrades
```

## VScodium

```
wget -qO - https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/raw/master/pub.gpg | gpg --dearmor | sudo dd of=/etc/apt/trusted.gpg.d/vscodium.gpg
echo 'deb https://paulcarroty.gitlab.io/vscodium-deb-rpm-repo/debs/ vscodium main' | sudo tee --append /etc/apt/sources.list.d/vscodium.list
sudo apt update 
sudo apt-get install codium 

```

## Avidemux

```
sudo add-apt-repository ppa:ubuntuhandbook1/avidemux
sudo apt-get install avidemux2.7-qt5
avidemux2.7_qt5 
history

```
