# go-archlinux

<p>Work of Progress<p>

## Reasons
Microsoft to abandon Windows 10 for 11 and unable to upgrade due to hardware?
<br><br>
Build a Gaming and/or Office PC and cannot decide which distro flavour?
<br><br>
Sticking with traditional technology and without or limited AI?
<br><br>
## Answer
Switching to Linux can save you money since it's free to use and often requires less powerful hardware than Windows. Additionally, Linux is generally more secure and customisable, making it a great option for users looking for a reliable operating system.
<br><br>
GO Arch Linux!<br>
$\color{green}{Gaming}$ and/or $\color{green}{Office}$ on Arch Linux with the help from a skilled Deaf long viking beard man. 🤘
<br><br>
Providing guides to install/customise with [Arch Linux](https://archlinux.org) building from scratch for the Deaf, DeafBlind, DeafDisabled, Hard of Hearing and Late-Deafened.
<br><br>
Hearing are welcome. Just don't ask with your mouth. 😜
<br><br><br><br>
Desktop Environment: [KDE Plasma](https://kde.org/plasma-desktop/)<br><br>
Software Included Example:<br>
[ClamAV](https://www.clamav.net), [Discord](https://discord.com), [Firewalld](https://firewalld.org), [GIMP](https://www.gimp.org), [ISO Image Writer](https://apps.kde.org/isoimagewriter), [Kalm](https://apps.kde.org/kalm), [LibreOffice](https://www.libreoffice.org/discover/screenshots), [Live Captions](https://github.com/abb128/LiveCaptions), [Proton Mail](https://proton.me/mail), [*Steam](https://store.steampowered.com/about), [Strawberry](https://www.strawberrymusicplayer.org), [Timeshift](https://github.com/linuxmint/timeshift), [VLC](https://www.videolan.org/vlc), [Yazi](https://github.com/sxyazi/yazi), [Zen Browser](https://zen-browser.app)
<br><br>
*Some games do not support on Linux. Moreover, if you only have IGPU (Integrated Graphics Processing Unit) such as [APU](https://en.wikipedia.org/wiki/AMD_APU) or [IGT](https://en.wikipedia.org/wiki/Intel_Graphics_Technology), check [ProtonDB](https://www.protondb.com) for Game on Linux compability including "Steam Deck" which is based on APU (in theory should work on IGT too) for your laptop or PC.
<br><br>
## Avoid At All Costs
+ ### $\textsf{\color{#ea4335}{AppImage - Storage Usage, Update Challenges, Compatibility Issues}}$
+ ### $\textsf{\color{#ea4335}{Discover - Slow Performance, Limited Support, Dependency Conflicts}}$
+ ### $\textsf{\color{#fbbc05}{Flatpak - Storage Usage, Sandboxing Restrictions, Slower Performance}}$
+ ### $\textsf{\color{#fbbc05}{Snap - Slower Execution, Centralised Control, Limited Transparency}}$
<br>

## Hardware Minimum Suggestion (vs Garmr's Hardware)
+ CPU: x86_64
+ CPU: 6/12 (8/16)
+ RAM: 32GB (64GB)
+ GPU: 16GB (24GB)
+ SSD: 2TB (2x 4TB)

## Linux's Graphics Driver List
+ AMD / ATI (open-source)
+ All open-source (Intel with Radeon or AMD with Arc)
+ Intel (open-source)
+ Nvidia (open kernel module for newer GPUs, Turing+)
+ Nvidia (proprietary)
+ VMware / Virtualbox (open-source)

## Instructions Included
+ check list (done)
+ priceless warning (done)
+ flash iso (done)
+ bios settings (done)
+ install arch linux (done)
+ repos & software (done)
+ security (finish tomorrow)
+ colors & themes (coming soon)

## Check List
What needs are:
+ One USB-C or USB Flash Drive, at least 2GB to iso.
+ One External HDD (Hard Disk Drive), External SSD (Solid-State Drive) or Flash Drive to backup.

## Priceless Warning - A Friendly Reminder
<p>If you haven't backed up your documents, downloads, photos, videos. Perhaps fonts and wallpapers. Browser's bookmark export. Anything else not mentioned?</p>
<p>Use external HDD, SSD or another Flash Drive... make sure you have enough space to store all of that. Usually default format is fat32 which is fine for now.</p>
<p>As a rule of thumb for backup, if your disk is almost full... follow internal disk capacity. If you have plenty of free spaces... another way to check is to create "Backup" folder and copy your specific folders/files over. When done, you can check total size on the Backup folder. If under 2TB, Flash Drive will do. If up to 4TB, External SSD will do. If over 6TB, External HDD will do.</p>
<p>Whenever you are ready... open file manager and open another file manager. Copy your stuff over to backup disk. It may be a while if you have large files. After done, double check to make sure that backup folders/files are there and open them with no error?</p>
<p>Done and ready to move on? Unplug Backup USB or USB-C.</p>

## Flash ISO

### Arch-Based
<p>sudo pacman -S rpi-imager</p>

### Debian/Ubuntu-Based
[Raspberry Pi Imager](https://www.raspberrypi.com/software)

### Raspberry Pi OS
<p>sudo apt install rpi-imager</p>

### Linux Flavours
<p>Check your OS's repo packages "rpi-imager". If no luck, alternatives are:<p>
<p>GNOME: gnome-multi-writer or impression</p>
<p>KDE: isoimagewriter</p>

### Mac
[Raspberry Pi Imager](https://www.raspberrypi.com/software)

### Windows
[Raspberry Pi Imager](https://www.raspberrypi.com/software)
<br><br>
After installing, reboot your computer for the application to recognise usb.
<br><br>
### Download Arch Linux ISO
<p>Scroll down to your country and pick whichever you like. Then select archlinux-current year and month-published day-x86_64.iso.</p>

[Download Arch Linux](https://archlinux.org/download)
<br><br>
<p>Insert USB or USB-C Flash Drive for ISO. Not your Backup disk!</p>
<p>Open Raspberry Pi Imager (or other app you prefer).</p>
<p>Raspberry Pi Device: NO FILTERING.</p>
<p>Operating System: ARCHLINUX-current year and month-published day-X86_64.ISO.</p>
<p>Storage: select your USB or USB-C.</p>
<p>Then hit NEXT. Yes if correct usb disk or No if wrong usb disk and try again.</p>
<p>Your password as consent to allow writing iso to usb.</p>
<p>Wait, be patient... when it's done, close the app.</p>

<img width="812" height="617" alt="rpi-imager" src="https://github.com/user-attachments/assets/22cd3e36-86f5-4589-a713-4658654030ee" /> <img width="812" height="617" alt="rpi-imager-os" src="https://github.com/user-attachments/assets/907fad62-708a-46be-92ca-0b7913a861d1" />

## BIOS Settings
<p>Reboot and press F2 or DEL during the inital boot process. If you're unsure or pressing F2 or DEL didn't do anything, hold power button and power on again. Look for a message on the screen during startup that indicates which key to press. For an example: HP use F10 and some Dell use F12</p>

<p>Boot Mode: UEFI</p>
<p>Fast Boot: Disabled</p>
<p>Secure Boot: Disabled</p>
<p>SATA: AHCI</p>
<p>Boot Priority: select the usb as the first boot option</p>

## Install Arch Linux
<p>Choose Arch Linux install medium (x86_64, UEFI). Press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161531" src="https://github.com/user-attachments/assets/dce83d1c-35b7-4a0f-8674-08f9eda9b4e6" />
<p>Until you see root@archiso, type archinstall. Press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161638" src="https://github.com/user-attachments/assets/ee978e8b-67c3-4a72-8c87-bf53dfec605d" />
<p>Select Mirrors and repositories, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161736" src="https://github.com/user-attachments/assets/95151f3a-ae39-400f-89dd-ae9cc9aa1d39" />
<p>Select regions, press enter. Select your country, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161814" src="https://github.com/user-attachments/assets/785eb459-62ff-49f9-84ff-9ce2108fc050" />
<p>Optional repositories, press enter. </p>
<img width="1280" height="720" alt="Screenshot_20251006_161853" src="https://github.com/user-attachments/assets/ff88ee70-2087-4d40-9fc6-88fc12da145e" />
<p>Select multilib, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161913" src="https://github.com/user-attachments/assets/e1b6308b-1da8-476e-8c16-84f4d24ccd51" />
<p>Disk configuration, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162113" src="https://github.com/user-attachments/assets/345118d6-e686-4115-8baf-f429bdc02f28" />
<p>Partitioning, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162137" src="https://github.com/user-attachments/assets/1eb78ca9-ab50-4456-a83b-cb107e1ae463" />
<p>Use a best-effort default partition layout, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162154" src="https://github.com/user-attachments/assets/7da93459-627f-4ac4-a0b1-9c71adb2364e" />
<p>Select ext4, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162250" src="https://github.com/user-attachments/assets/94317a10-f891-4744-9802-4a101539b977" />
<p>Disk encryption, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162329" src="https://github.com/user-attachments/assets/3db0dcc8-0d58-4fd6-a4a1-97fb8e5bdfc0" />
<p>Encryption type, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162343" src="https://github.com/user-attachments/assets/b239734e-7761-4733-9db2-1b8dea020e30" />
<p>LUKS, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162356" src="https://github.com/user-attachments/assets/cbf17d96-edcb-4bc1-9d8f-3b015fcc820d" />
<p>Encryption password, press enter. Create a password, don't forget to write down or use a password manager on phone. Press enter, password again, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162435" src="https://github.com/user-attachments/assets/43d01be7-105f-47f9-ac83-92ed3afe3637" />
<p>Partitions, press enter. </p>
<img width="1280" height="720" alt="Screenshot_20251006_162528" src="https://github.com/user-attachments/assets/3330e329-cb35-4541-b46a-74e3e1a391b7" />
<p>Usally one option, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162559" src="https://github.com/user-attachments/assets/9550d615-f320-4f83-9723-f4e93437059d" />
<p>Swamp, press enter. If RAM is under 16GB, select yes. If RAM is over 32GB, select no. Press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162708" src="https://github.com/user-attachments/assets/2f9b1f27-bf3f-48bd-80d0-7d75490905d4" />
<p>Bootloader, press enter. Select GRUB, press enter.</p>
<p>Hostname, press enter. Optional to change archlinux. Press enter.</p>
<p>Authentication, press enter. User account, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162818" src="https://github.com/user-attachments/assets/2e251a7e-0ffd-4251-a9e5-a4166ef0ea1e" />
<p>Add a user, press enter. (Don't forget to write down or add another to password manager.) Should "yourname" be a superuser (sudo)? Select Yes, press enter. Confirm and exit, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162941" src="https://github.com/user-attachments/assets/02c33bfa-1cfc-493c-8e1c-5063dbe01c27" />
<p>Profile, press enter. Type, press enter. Desktop, press enter. Select KDE Plasma, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163038" src="https://github.com/user-attachments/assets/48d8ddca-a617-4e5c-ba3b-2b0a3e22b205" />
<p>Graphics driver, press enter. Select the correct driver for your PC, perss enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163051" src="https://github.com/user-attachments/assets/065e697c-cee5-4b63-8783-118462f4b0c5" />
<p>Applications, press enter. Bluetooth, yes, press enter. Audio, pipewire, press enter.</p>
<p>Kernels, press enter. Unselect linux and select linux-zen, press enter</p>
<img width="1280" height="720" alt="Screenshot_20251006_163358" src="https://github.com/user-attachments/assets/13ccb3bb-974c-4ceb-9863-06865670b1de" />
<p>Network configuration, press enter. Use Networkmanager (necessary to configure internet graphically in GNOME and KDE Plasma), press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163515" src="https://github.com/user-attachments/assets/391c79b9-e62a-43de-bc3e-e1e56bdb76c6" />
<p>Timezone, press enter. Select your timezone, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163634" src="https://github.com/user-attachments/assets/ea12134b-d7d7-464b-b7ab-30e8ecf4e838" />
<p> Install, press enter. Yes, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163702" src="https://github.com/user-attachments/assets/3c1f3ab0-5e84-44a0-bd61-60b9bfb10856" />
<p>Reboot system, press enter. Be ready to unplug Flash Drive during temporarily shutdown (black screen).</p>
<img width="1280" height="720" alt="Screenshot_20251006_164221" src="https://github.com/user-attachments/assets/34f2f1ee-9eaa-4981-9acc-27359d1e887b" />

## Repos & Software

### Add Chaotic-AUR Repository
<p>On the keyboard, press CTRL+ALT+T to open a terminal.</p>

<p>Key, Signing and Mirrorlist</p>

`sudo pacman-key --recv-key 3056513887B78AEB --keyserver keyserver.ubuntu.com`

`sudo pacman-key --lsign-key 3056513887B78AEB`

`sudo pacman -U 'https://cdn-mirror.chaotic.cx/chaotic-aur/chaotic-keyring.pkg.tar.zst' 'https://cdn-mirror.chaotic.cx/chaotic-aur/chaotic-mirrorlist.pkg.tar.zst'`
<br><br>
`sudo nano /etc/pacman.conf`

<p>Add to the bottom. Paste, press CTRL+SHIFT+V</p>

```
[chaotic-aur]
Include = /etc/pacman.d/chaotic-mirrorlist
```
<img width="1280" height="720" alt="Screenshot_20251008_135622" src="https://github.com/user-attachments/assets/c0fef24b-8d6a-4ae8-916d-b4cf89121eb5" />

<p>Press CRTL+X, Y, ENTER</p>

<p>Refresh pacman update...</p>

`sudo pacman -Syu`

### Add Packages

`sudo pacman -S clamav discord libappindicator-gtk3 xdg-utils firewalld libnotify python-pyqt6 gimp isoimagewriter kalm libreoffice-fresh paru steam strawberry gst-libav timeshift vlc vlc-plugin-ass vlc-plugin-ffmpeg vlc-plugin-freetype vlc-plugin-mpeg2 vlc-plugin-notify vlc-plugin-srt vlc-plugin-x264 vlc-plugin-x265 yazi ffmpeg imagemagick poppler zen-browser-bin`

### Add Other AUR Packages
`paru -S livecaptions proton-mail-bin`

### Remove Unnecesarry Packages
<p>KDE's Discover package manager is not designed for Arch Linux.</p>

`sudo pacman -R plasma-meta`

`sudo pacman -R discover`

## Security

### Antivirus
#### ClamAV

According to [ArchWiki](https://wiki.archlinux.org/title/ClamAV#Configuration) recommended configurations.

I have modified [clamd.conf](https://github.com/dovgarmr/go-archlinux/blob/main/clamd.conf) to match to make our lives easier.

`sudo nano /etc/sudoers.d/clamav`

```
clamav ALL = (ALL) NOPASSWD: SETENV: /usr/bin/notify-send
```
<p>Press CTRL+X, Y, ENTER</p>

`sudo nano /etc/clamav/virus-event.bash`

```
#!/bin/bash
PATH=/usr/bin
ALERT="Signature detected by clamav: $CLAM_VIRUSEVENT_VIRUSNAME in $CLAM_VIRUSEVENT_FILENAME"

# Send an alert to all graphical users.
for ADDRESS in /run/user/*; do
    USERID=${ADDRESS#/run/user/}
    /usr/bin/sudo -u "#$USERID" DBUS_SESSION_BUS_ADDRESS="unix:path=$ADDRESS/bus" PATH=${PATH} \
        /usr/bin/notify-send -u critical -i dialog-warning "Virus found!" "$ALERT"
done
```

Dinner and call it a night. Update tomorrow.



### DNS

<p>At the bottom left of the screen, click Application Launcher> System> System Settings</p>
<p>Wi-Fi & Internet, preferable Wired connection. If using Wireless, similar.</p>
<p>IPv4</p>
<p>Methods:</p> 
<p>Automatic (Only addresses)</p>
<p>DNS Servers:</p>

`9.9.9.9,149.112.112.112`

<p>IPv6</p>
<p>Methods:</p> 
<p>Automatic (Only addresses)</p>
<p>DNS Servers:</p>

`2620:fe:fe,2620:fe::9`

<p>Click Apply. Close the app. Reboot the PC.</p>

<p>Open Zen Browser. If you have Firefox account, you can sync. Or import your bookmark from Backup disk.</p>
<p>Click on ... to Settings, Privacy & Security. Scroll down to DNS over HTTPS. Choose Off</p>
<img width="1261" height="1354" alt="Screenshot_20251008_143726" src="https://github.com/user-attachments/assets/d8d466c1-635d-4562-a01b-981816a5bf35" />

### Firewall

`sudo systemctl enable firewalld && sudo systemctl start firewalld`

`firewall-cmd --get-active-zones`

`firewall-cmd --list-all-zones`

`nmcli connection show`

`firewall-cmd --get-default-zone`

`firewall-cmd --set-default-zone=home`

`firewall-cmd --get-services`

## Colors & Themes
