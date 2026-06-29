# DeadBeef config
## preview
![screenshot](./preview1.png)
## How to install
### Linux
#### 1) install deadbeef and waveform seekbar plugin via aur (yay for example)
#### Arch linux
----
**!!Warning!!** These packages may be compromised. Check the safety of the packages before installation
```bash
yay -S --needed deadbeef deadbeef-plugin-waveform-gtk3-git
```
#### Debian (Ubuntu, Mint, etc)
----
install [deadbeef](https://sourceforge.net/projects/deadbeef/files/Builds/1.10.2/linux/deadbeef-static_1.10.2-1_amd64.deb/download) and [waveform seekbar plugin](https://github.com/cboxdoerfer/ddb_waveform_seekbar)
> If you dont want to install any plugins, you can just skip it. Dont forget to change seekbar to default

#### Other Linux distro
----
Check https://deadbeef.sourceforge.io/download.html and https://github.com/cboxdoerfer/ddb_waveform_seekbar

#### 2) copy deadbeef config folder to ~/.config/
```bash
mkdir -p ~/.config/deadbeef/
git clone https://github.com/ini-qstm/deadbeef-config.git ~/.config/deadbeef/
```
#### 3) if you want, you also can install [Discord Rich Presence Plugin](https://github.com/kuba160/ddb_discord_presence):
> doesnt work with not configure flatpak discord. See https://github.com/flathub/com.discordapp.Discord/wiki/Rich-Precense-(discord-rpc) for guide to configure flatpak application
1. download plugin [here](https://github.com/kuba160/ddb_discord_presence/releases/)
2. unzip and move to deadbeef's folder:
```bash
mkdir -p ~/.local/lib/deadbeef/
# replace "archive.zip" with archive name
unzip archive.zip -d ~/.local/lib/deadbeef/
``` 

### Windows
----
Please, use something more popular like foobar2000, aimp, etc. You dont need deadbeef

### MacOS
----
> You will need to change seekbar to default
1) install [deadbeef](https://deadbeef.sourceforge.io/download.html). You also can download [Discord Rich Presence Plugin](https://github.com/kuba160/ddb_discord_presence) and unpack zip, then copy *.dylib files into ~/Library/Application Support/Deadbeef/Plugins
2) download this repo and insert to deadbeef directory. idk where this dir, maybe at ~/Library/Application Support/Deadbeef/. Find "config" file and replace it

## Quick configure:
1) start deadbeef
2) edit -> preferences -> sound: select your output device
3) edit -> preferences -> media library: click to plus (from below) and then select your music library
4) Most likely, you will need to change colors for the seekbar (if you use the waveform seekbar), and the playback control buttons. To do this, go to View → Click to Design Mode (turn it on). Right-click on those elements → Configure, and there you can change the colors to whatever you like. after do view -> click to design mode (turn off)


#### If you dont like waveform seekbar or you cant install it, you need:
1) view -> click to design mode (turn on)
2) rmb click on seekbar -> replace with... -> seekbar (its a default seekbar)
3) view -> click to design mode (turn off)

plugins and manuals you can find at https://deadbeef.sourceforge.io/

## Credits
[deadbeef](https://deadbeef.sourceforge.io/)
