# debian install multiple platforms

## debian:stable

## platform

- intel -> Apple Mac Pro 2017
- aarch64 -> raspi
 
### intel -> Apple Mac Pro 2017

#### requirement
- usb stick > 8GByte
- [USB-C adapter to USB-A](https://www.viewsonic.com/library/tech/usb-c-usb-b-and-usb-a-whats-the-difference/)
- running mac os system
- [balena Etcher](https://etcher.balena.io/) download and install to macos
- debian iso => [debian-12.6.0-amd64-netinst.iso](https://www.debian.org/download) download to macos

#### prepare usb stick
1. connect the USB stick with the computer
2. start balena etcher
3. select the iso file from your download folder
4. select the plugin usb stick
5. select flash
6. wait for finished process
7. shutdown the computer

#### prepare your mac disk with diskutil - not completed need improvement
1. open the tool diskutil
2. select our hd
3. choose tab entry partition
4. reduce the akt partition - you need min 32GByte
5. in the new free space create a new partition NOT volumes with name Linux and Format MsDos32 - click the + sign
6. notice the size of the new partition - is very helpful to find the in the next steps
7. close all app and widows and SHUTDOWN the computer


#### install debian
1. hold the LEFT option key
2. touch once on/off key
3. wait to show the disk menu
4. select

