# Notes for base 20.04 install

If you were wondering how this computer does on Linux (5.4.0), I got some good news for you:
Installation notes: disable secure boot and Intel Rapid Storage Technology as usual.
Everything works as expected out of the box (Ubuntu 20.04 installer), except for the fingerprint reader and automatic brightness control. I am happy to report that the touchpad works really well.
You'll want the 440.82 Nvidia driver, 435.21 doesn't recognize the discrete graphics card. PRIME works very well.

OR

This guy has some good stuff too!:

https://medium.com/@asad.manji/my-journey-installing-ubuntu-20-04-on-the-dell-xps-15-9500-2020-8ac8560373d1



# Ubuntu Focal Fossa 20.04 Setup on XPS 13 9300

```bash
wget https://raw.githubusercontent.com/jules-ch/Ubuntu20-Setup-XPS13/master/setup.sh && sudo chmod +x setup.sh && ./setup.sh
```

## Prerequisistes

XPS 9300 comes with Bionic Beaver 18.04 pre-installed. 
Upgrade Ubuntu to 20.04 before executing this script.

## General

- **Shell** : Gnome Shell
- **Gnome extensions** : [Material Shell](https://github.com/material-shell/material-shell)
- **Theme** : [Plata Theme Noir](https://gitlab.com/tista500/plata-theme)
- **Icon** : [Tela](https://github.com/vinceliuice/Tela-icon-theme)
- **Fonts** :
  - Open Sans (Interface)
  - Fira Code Retina (Mono)

- Drivers from dell focal repository
- Fingerprint reader
- [Fusuma](https://github.com/iberianpig/fusuma) for handling trackpad gestures
- [Howdy](https://github.com/boltgolt/howdy) for authentication with facial recognition **(Optional)**


## Social

- Discord
- Thunderbird

## Software management

- gnome-software + flatpak plugin
- Flatpak

## Development

- Visual Studio Code
- Docker
- Postman
- Python 3
- Java (OpenJDK 11 LTS)
- Web Development (Node.js LTS + Yarn) **(Optional)**
- Mobile Development (Android Studio 4.1) **(Optional)**
    
## Multimedia

- Spotify
- VLC
- GIMP



## Notes for fixing NVIDIA drivers

https://linuxconfig.org/how-to-install-the-nvidia-drivers-on-ubuntu-20-04-focal-fossa-linux

or you can shut them off

https://gist.github.com/deimi/e1dc28d3e4c6f267f500533be6ac126c
