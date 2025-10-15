# go-archlinux

## Reasons
Microsoft to abandon Windows 10 for 11 and unable to upgrade due to hardware?
<br><br>
Build a Gaming and/or Office PC and cannot decide which distro flavour?
<br><br>
Sticking with traditional technology and without or limited AI?
<br><br>
## Answer
Switching to Linux can save you money since it's free to use, works on old and new hardware. Additionally, Linux is generally more privacy, secure and customisable, making it a great option for users looking for a reliable operating system.
<br><br>
GO Arch Linux!<br>
$\color{green}{Gaming}$ and/or $\color{green}{Office}$ on Arch Linux with the help from a skilled Deaf man with long viking beard. 🤘
<br><br>
Providing guides to install/customise with [Arch Linux](https://archlinux.org) building from scratch for the Deaf, DeafBlind, DeafDisabled, Hard of Hearing and Late-Deafened.
<br><br>
Hearing are welcome. Just don't ask with your mouth. 😜
<br><br><br><br>
Desktop Environment: [KDE Plasma](https://kde.org/plasma-desktop/)<br><br>
Software Example:<br>
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
+ security (done)
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
`sudo pacman -S rpi-imager`

### Debian/Ubuntu-Based
[Raspberry Pi Imager](https://www.raspberrypi.com/software)

### Raspberry Pi OS
`sudo apt install rpi-imager`

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

<img width="812" height="617" alt="rpi-imager" src="https://github.com/user-attachments/assets/a156a578-8faa-4692-82c3-fef319f2bc10" /> <img width="812" height="617" alt="rpi-imager-os" src="https://github.com/user-attachments/assets/5d04e690-1fb9-4201-b18b-48a80f990dba" />

## BIOS Settings
<p>Reboot and press F2 or DEL during the inital boot process. If you're unsure or pressing F2 or DEL didn't do anything, hold power button and power on again. Look for a message on the screen during startup that indicates which key to press. For an example: HP use F10 and some Dell use F12</p>

<p>Boot Mode: UEFI</p>
<p>Fast Boot: Disabled</p>
<p>Secure Boot: Disabled</p>
<p>SATA: AHCI</p>
<p>Boot Priority: select the usb as the first boot option</p>

## Install Arch Linux
<p>Choose Arch Linux install medium (x86_64, UEFI). Press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161531" src="https://github.com/user-attachments/assets/0292fb41-6432-4598-b152-cab23c8b3f33" />
<p>Until you see root@archiso, type archinstall. Press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161638" src="https://github.com/user-attachments/assets/2fb77912-5665-4f63-a7b9-b9814db6b044" />
<p>Select Mirrors and repositories, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161736" src="https://github.com/user-attachments/assets/dbc1094f-32a3-48ee-ac95-76544ab9b019" />
<p>Select regions, press enter. Select your country, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161814" src="https://github.com/user-attachments/assets/a7c3ac3a-c3cf-4e39-8afd-3424d6d9b22f" />
<p>Optional repositories, press enter. </p>
<img width="1280" height="720" alt="Screenshot_20251006_161853" src="https://github.com/user-attachments/assets/1579a478-3ca8-4c0c-9e79-483a1ce2000c" />
<p>Select multilib, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_161913" src="https://github.com/user-attachments/assets/e6649f40-9dd0-4290-b939-07588753025c" />
<p>Disk configuration, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162113" src="https://github.com/user-attachments/assets/a4119d49-d3bf-4b5a-8882-b5509201b7d5" />
<p>Partitioning, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162137" src="https://github.com/user-attachments/assets/4da58a97-f7ad-4c36-be7d-73264eff4f01" />
<p>Use a best-effort default partition layout, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162154" src="https://github.com/user-attachments/assets/6c3dfa6c-6bc5-4698-868e-63168821b3a9" />
<p>Select ext4, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162250" src="https://github.com/user-attachments/assets/3d0d9463-fa64-42fc-b4c0-54cc72f71cd7" />
<p>Disk encryption, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162329" src="https://github.com/user-attachments/assets/b3b98129-0532-4a3e-8644-e9f96be7517f" />
<p>Encryption type, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162343" src="https://github.com/user-attachments/assets/38372177-8927-4a72-9ed1-cb9f3f5bfd2f" />
<p>LUKS, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162356" src="https://github.com/user-attachments/assets/aab9eae0-bc6f-44be-86f6-0a4305d5f16c" />
<p>Encryption password, press enter. Create a password, don't forget to write down or use a password manager on phone. Press enter, password again, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162435" src="https://github.com/user-attachments/assets/10ea6799-be30-4fb7-a916-c6695f26960b" />
<p>Partitions, press enter. </p>
<img width="1280" height="720" alt="Screenshot_20251006_162528" src="https://github.com/user-attachments/assets/dd98be3b-4c68-47ca-83bb-2dfba0259985" />
<p>Usally one option, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162559" src="https://github.com/user-attachments/assets/4f0aa4d5-95dc-41d3-8a62-bf78b865208c" />
<p>Swamp, press enter. If RAM is under 16GB, select yes. If RAM is over 32GB, select no. Press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162708" src="https://github.com/user-attachments/assets/1dce3785-7c97-41fe-ba3b-24bde11193fc" />
<p>Bootloader, press enter. Select GRUB, press enter.</p>
<p>Hostname, press enter. Optional to change archlinux. Press enter.</p>
<p>Authentication, press enter. User account, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162818" src="https://github.com/user-attachments/assets/28c1ca94-23d9-40dd-ae3c-08ec91ced7f2" />
<p>Add a user, press enter. (Don't forget to write down or add another to password manager.) Should "yourname" be a superuser (sudo)? Select Yes, press enter. Confirm and exit, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_162941" src="https://github.com/user-attachments/assets/cab027d8-3763-402c-95f9-93ae10a0db7c" />
<p>Profile, press enter. Type, press enter. Desktop, press enter. Select KDE Plasma, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163038" src="https://github.com/user-attachments/assets/65628875-4967-44fa-a333-c546d3287413" />
<p>Graphics driver, press enter. Select the correct driver for your PC, perss enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163051" src="https://github.com/user-attachments/assets/72046699-f519-43f2-99f1-298b6f2ab551" />
<p>Applications, press enter. Bluetooth, yes, press enter. Audio, pipewire, press enter.</p>
<p>Kernels, press enter. Unselect linux and select linux-zen, press enter</p>
<img width="1280" height="720" alt="Screenshot_20251006_163358" src="https://github.com/user-attachments/assets/c1e4ec65-c267-4110-b888-19b59854b142" />
<p>Network configuration, press enter. Use Networkmanager (necessary to configure internet graphically in GNOME and KDE Plasma), press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163515" src="https://github.com/user-attachments/assets/4f71dc22-4fa3-4339-8de5-884cfaa2a2d1" />
<p>Timezone, press enter. Select your timezone, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163634" src="https://github.com/user-attachments/assets/5d327cdc-9f8b-403a-9580-bb9da5997e50" />
<p> Install, press enter. Yes, press enter.</p>
<img width="1280" height="720" alt="Screenshot_20251006_163702" src="https://github.com/user-attachments/assets/54c8fd9f-a475-457e-823a-c78a467bebc2" />
<p>Reboot system, press enter. Be ready to unplug Flash Drive during temporarily shutdown (black screen).</p>
<img width="1280" height="720" alt="Screenshot_20251006_164221" src="https://github.com/user-attachments/assets/ce7c48d8-ece9-43e8-a92e-c8e9851f6438" />

## Repos & Software

### Remove Unnecesarry Packages
<p>KDE's Discover package manager is not designed for Arch Linux.</p>
<p>On the keyboard, press CTRL+ALT+T to open a terminal.</p>

`sudo pacman -R plasma-meta`

`sudo pacman -R discover`

### Add Chaotic-AUR Repository
<p>Key, Signing and Mirrorlist</p>

`sudo pacman-key --recv-key 3056513887B78AEB --keyserver keyserver.ubuntu.com`

`sudo pacman-key --lsign-key 3056513887B78AEB`

`sudo pacman -U 'https://cdn-mirror.chaotic.cx/chaotic-aur/chaotic-keyring.pkg.tar.zst' 'https://cdn-mirror.chaotic.cx/chaotic-aur/chaotic-mirrorlist.pkg.tar.zst'`
<br><br>
`sudo nano /etc/pacman.conf`

```
[chaotic-aur]
Include = /etc/pacman.d/chaotic-mirrorlist
```
Add to the bottom

<img width="1280" height="720" alt="Screenshot_20251008_135622" src="https://github.com/user-attachments/assets/ce36ade3-390e-443f-8b5b-117913526cc5" />

<p>Press CRTL+X, Y, ENTER</p>

<p>Refresh pacman update...</p>

`sudo pacman -Syu`

### Add Packages
<p>Choose Full, No Gaming or No Office.</p>

#### Full
`sudo pacman -S clamav clamav-unofficial-sigs discord firewalld python-pyqt6 gimp isoimagewriter kalm libreoffice-fresh paru steam strawberry gst-libav timeshift vlc vlc-plugin-ass vlc-plugin-ffmpeg vlc-plugin-freetype vlc-plugin-mpeg2 vlc-plugin-notify vlc-plugin-srt vlc-plugin-x264 vlc-plugin-x265 yazi imagemagick zen-browser-bin`
#### No Gaming
`sudo pacman -S clamav clamav-unofficial-sigs discord firewalld python-pyqt6 gimp isoimagewriter kalm libreoffice-fresh paru strawberry gst-libav timeshift vlc vlc-plugin-ass vlc-plugin-ffmpeg vlc-plugin-freetype vlc-plugin-mpeg2 vlc-plugin-notify vlc-plugin-srt vlc-plugin-x264 vlc-plugin-x265 yazi imagemagick zen-browser-bin`
#### No Office
`sudo pacman -S clamav clamav-unofficial-sigs discord firewalld python-pyqt6 gimp isoimagewriter kalm paru steam strawberry gst-libav timeshift vlc vlc-plugin-ass vlc-plugin-ffmpeg vlc-plugin-freetype vlc-plugin-mpeg2 vlc-plugin-notify vlc-plugin-srt vlc-plugin-x264 vlc-plugin-x265 yazi imagemagick zen-browser-bin`

#### No Gaming and Office
`sudo pacman -S clamav clamav-unofficial-sigs discord firewalld python-pyqt6 gimp isoimagewriter kalm paru strawberry gst-libav timeshift vlc vlc-plugin-ass vlc-plugin-ffmpeg vlc-plugin-freetype vlc-plugin-mpeg2 vlc-plugin-notify vlc-plugin-srt vlc-plugin-x264 vlc-plugin-x265 yazi imagemagick zen-browser-bin`

### Add AUR Packages
`paru -S livecaptions proton-mail-bin`

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

`sudo systemctl edit --full clamav-clamonacc.service`

<p>Compare below, similar? And notice under [Service], ExecStart= and --fdpass are not there? Add yourself or copy and paste.</p>

```
# clamonacc systemd service file primarily the work of ChadDevOps & Aaron Brighton
# See: https://medium.com/@aaronbrighton/installation-configuration-of-clamav-antivirus-on-ubuntu-18-04-a6416bab3b41#a340

[Unit]
Description=ClamAV On-Access Scanner
Documentation=man:clamonacc(8) man:clamd.conf(5) https://docs.clamav.net/
Requires=clamav-daemon.service
After=clamav-daemon.service syslog.target network.target

[Service]
Type=simple
User=root
ExecStartPre=/bin/bash -c "while [ ! -S /run/clamav/clamd.ctl ]; do sleep 1; done"
ExecStart=
ExecStart=/usr/sbin/clamonacc -F --fdpass --log=/var/log/clamav/clamonacc.log
ExecStop=/bin/kill -SIGKILL $MAINPID

[Install]
WantedBy=multi-user.target
```
Press CTRL+X, Y, ENTER

`sudo freshclam`

`sudo touch /var/log/clamav/freshclam.log`

`sudo chmod 600 /var/log/clamav/freshclam.log`

`sudo chown clamav /var/log/clamav/freshclam.log`

`sudo systemctl start clamav-freshclam.service`

`sudo systecmtl enable clamav-freshclam.service`

`sudo systemctl start clamav-daemon.service`

`sudo systemctl enable clamav-daemon.service`

`sudo systemctl start clamav-clamonacc.service`

`sudo systemctl enable clamav-clamonacc.service`

`sudo touch /run/clamav/clamd.ctl`

`sudo chown clamav:clamav /run/clamav/clamd.ctl`

`sudo systemctl restart clamav-daemon.service`

#### Testing
`curl https://secure.eicar.org/eicar.com.txt | clamscan -`
The output must include: stdin: Win.Test.EICAR_HDB-1 FOUND

#### Real-Time Protection
`cd Downloads`

`wget https://secure.eicar.org/eicar.com.txt`

`cat eicar.com.txt`

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

<img width="1515" height="812" alt="Screenshot_20251010_174943" src="https://github.com/user-attachments/assets/6cc6f4cf-2c62-41fe-ab4d-cbc56702f525" />

<p>Click Apply. Close the app. Reboot the PC.</p>

<p>Open Zen Browser. If you have Firefox account, you can sync. Or import your bookmark from Backup disk.</p>
<p>Click on ... to Settings, Privacy & Security. Scroll down to DNS over HTTPS. Choose Off</p>
<img width="1261" height="1354" alt="Screenshot_20251008_143726" src="https://github.com/user-attachments/assets/e8738ff6-0cf7-44d3-902f-2928dbd00404" />

Confirm you're using Quad9 by visiting [on.quad9.net](https://on.quad9.net).

### Firewall

`sudo systemctl enable firewalld && sudo systemctl start firewalld`

`firewall-cmd --get-active-zones`

`firewall-cmd --list-all-zones`

`nmcli connection show`

`firewall-cmd --get-default-zone`

`firewall-cmd --set-default-zone=home`

`firewall-cmd --get-services`

## Colors & Themes
