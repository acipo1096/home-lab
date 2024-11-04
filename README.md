# Home Lab

## Computers

### Custom Built PC

#### Background

In 2019, I earned my first IT certification, the CompTIA A+. While I was happy my hard work paid off, and while I could describe all the parts of a PC, I had never really taken a PC apart before. I knew my certification would be more meaningful if I could back it up with a tangible project. So in January 2020, I headed over to Micro Center and got the parts I needed.

#### Parts

I used the following components in my PC:
- **CPU:** AMD Ryzen 5 2400G with Radeon Vega Graphics 3.60 GHz
- **Memory**: 16 GB RAM (I'd eventually upgrade to 32 GB of RAM a few years later)
- **Motherboard**: Gigabyte B450M DS3H WIFI
- **Storage**:
  - SanDisk 1TB SSD
  - Later, after my old MacBook Pro 2012 was recycled, I removed the Samsung 1TB SSD from that machine and inserted it into my PC to be used as a hard drive for my games
- **Graphics Card**: Radeon RX 580 Series
- **Operating System:** Windows 10 for Education
- **Case**: Cooler Master N200

#### Impact

I built my PC just in time. Barely a month later, COVID had taken over the world, and I eventually found myself furloughed and under lockdown. My new machine was the perfect start to begin working on home practice labs to hone the skills I had earned in two other certifications, the CompTIA Network+ and Security+. It was also a great machine to start running Cisco CCNA labs and begin working on my coding skills. And for the moments I wanted a break, I could play old games on Steam!

#### Future Plans

Unfortunately, my computer will not support Windows 11. I plan to build a newer, better PC within the next year. I intend to turn my current PC into a Proxmox server, which I can use to host web apps, additional file storage, and maybe home automation.

### Lenovo ThinkCentre Web Server

#### Background

In September 2024, my church was starting to get rid of some old computers, and I was able to take this one home. I decided to use it as a web server to host a website for my music. (For more information, see https://github.com/acipo1096/music-website.)

#### Setup

I was originally going to make this computer my new PC and make the PC above into a server. However, I had no set ideas for projects at the time other than my website, and I still needed something powerful for everyday use. 

My original plan was to install Ubuntu Server on the ThinkCentre, but it kept running into installation issues. I ultimately decided to install Proxmox (a) so I could have the flexibility to run multiple VMs if I needed to, and (b) because the installation succeeded where Ubuntu Server didn't.

#### Future Plans

I'll most likely convert this PC into a Linux client or may find another use for it as a server. It also will not be able to run Windows 11.

## Networking

My web server is segmented behind a TP-Link Omada ER605 VPN router for security and network segmentation. The devices on my local LAN cannot communicate with the server.

## NAS

### Synology DS220+

Used primarily as a backup for personal files. Also syncs with Google Drive and OneDrive for extra backups. I also host two custom web apps here: a Broadway Rankings app (https://github.com/acipo1096/guitar-song-style-randomizer) and a Guitar Song Randomizer (https://github.com/acipo1096/guitar-song-style-randomizer).

### Synology DS220j

My first NAS, purchased at the end of 2020. It runs much more slowly than my 220+. I use it primarily for Time Machine backups and backups for some files stored on the 220+.

## Diagram

![alt text](https://github.com/acipo1096/home-lab/blob/main/Home%20Lab.drawio.png "Home lab network diagram")

[logo]: https://github.com/acipo1096/home-lab/blob/main/Home%20Lab.drawio.png "Home lab network diagram"
