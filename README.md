# Linux Boot Sound 
A script to enable a custom boot sound on your linux distro!

# Requierments
A linux distro that uses systemd
aplay (should be preinstalled, if not check in your distros repos and install it)

# Note
While every distro is supposed to work, there might be some distros that don't, check [tested distros](https://github.com/axtloss/linux-boot-sound#supportedtested-distros) for more information
If you tested a distro not listed in [tested distros](https://github.com/axtloss/linux-boot-sound#supportedtested-distros) either update the README yourself or just open a new thread in issues with the label "Distro test"

# Installation
The installation procedure should be the same for every distro

```sh
git clone https://github.com/axtloss/linux-boot-sound.git
cd linux-boot-sound
chmod +x bootsoundInstaller
./bootsoundInstaller
```
the script will guide you through the rest

# Supported/tested distros

| Distro | State |
| ------ | ----- |
| Arch    | tested twice, not working |
| ubuntu(based distros)  | tested, working |
| Debian  | untested, should work as ubuntu also works |
| Fedora  | untested |
| Gentoo  | untested |

If you don't see your distro here fell free to test it and update the README or open a thread in issues with the label "Distro test"

# Roadmap

- a gui (probably using zenity or gtk)
- runit and OpenRC support

If you want to add these things yourself, feel free to fork this repo and adding them, if they work well I will commit them into this repo
