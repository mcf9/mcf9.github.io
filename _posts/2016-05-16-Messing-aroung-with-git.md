---
layout: post
title: Raspberry Pi for audio streaming
subtitle: Using Pi MusicBox
bigimg: /img/bcn2.JPG
---

I had a Raspberry Pi 2 sitting aroung unused. Since I also had a couple of Bose speaker that sound nice I wanted to find something to stream web radio. Potentially to also do Airplay.

[Pi MusicBox](http://www.pimusicbox.com/) delivered just that. Webradio and Airplay support.

Everything ~~is~~ was cool. Somehow I managed to mess up the configuration and now the Pi won’t boot properly. Thus I have to redo the setup.

## Setup
- Rasbberry Pi
- Edimax WiFi dongle 
- Small poweradapter incl. USB cable
- 16GB SD Card
- Bose speakers with analog audio cable
- _Note: I did not use a fancy USB Soundcard as most people suggest. To me the output is sufficient and there is no cracking whatsoever_

You can setup MusicBox manually, but I’ll just use the provided [SD-Card image](https://dl.mopidy.com/pimusicbox/pimusicbox-0.6.0.zip).

## Steps
1. Download Image
2. Grab [Pi Filler](http://elinux.org/RPi_Easy_SD_Card_Setup) for OS X 
3. Restore the image to SD-Card …
4. After successfully restoring the image, we have to provide the WiFi SSID and PW
5. Go to the SD-Card config/settings.ini
Provide the values without any brackets/quotes
6. You can set ’’enable_ssh = true’’ to enable SSH
7. Put the SD-Card into the Pi and fire it up

After a couple of minutes the Pi should show up as _MusicBox_. It is available through its ip and musicbox.local

I disabled all services, except: TuneIn, Podcasts, Youtube. Scanning for local files is done during boot, thus booting might take a while. 

The interface is available from any webbrowser on the same network. I use a remote controlled power outlet to turn on the speakers. The Pi is always-on. As I was redoing the steps from a couple of months ago, I noticed how it literally only took me *10 mins*. It is such a brilliant way to have play music, especially when I want to listen to radom web radio.

