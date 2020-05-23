#### kazam_1.4.5-3 Microphone bug Ubuntu 20.04 LTS
Ubuntu 20.04 has a problem with showing Microphone Unknown.
This problem can be solved by these commands.

##### Note: Please [Uninstall](README.md#uninstall-old-kazam)  the old files before you install the new ones


## Installation

```bash
wget -O kazam.deb https://bit.ly/kazam-deb
```
```bash
sudo dpkg -i kazam.deb
```
```bash
sudo apt install -f
```


## Uninstall Old Kazam
```bash
sudo apt-get remove kazam 
```
```bash
sudo apt-get remove --auto-remove kazam 
```
```bash
sudo apt-get purge kazam 
```
```bash
sudo apt-get purge --auto-remove kazam 
```
```bash

```
