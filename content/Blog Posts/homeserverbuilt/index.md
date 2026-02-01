---
title: "I built my first home server"
description: "I built my first home server"
date: 2026-01-30
categories: "Home Lab"
---

## Preview

Today I will post in my blog a post about my home server build. I started the homelab experience with a raspberry pi and casaOS and then upgraded to a thinkcentre. But I wanted more, so I investigated and bought some components to assembly my own home server, and it was actually my first PC building experience.


## Server Specs

RAM : 16 GB | 2400Mhz 

CPU : i5 8400

PSU : 450W | SFX

Motherboard : TUF B360M-E GAMING

SSD Nvme : 128 GB M.2

Disks : 2x 256GB SSD (At the time of this post I upgraded to 2x 2TB HDDs)

Case : Jonsbo N4

## Building the computer


### Assembling

I saw some people when building computers they built them on the floor like on top a cardboard or something like that, so I tried the same. Now I was unscrewing the top part of the case, so I could take it off.

But then my back was starting to hurt so I just placed the server on my desk, then I screwed the motherboard on the case but I didn't remember to put the backplate so I needed to take the motherboard off put the back plate (That took too long), and place the motherboard again, and screw it in place. 

Then it was time to put the thermal paste on the CPU, the one that was there, was there for a long time, so I just picked up some toilet paper and cleaned the CPU cooler and the CPU and put the thermal paste.

Now I just opened the PSU box and screwed it on a panel that comes off the case. But first I tried to place my 2.5 inch SSDs, and I needed to put something that looked like a rubber wheel, but I could put the screws on the SSDs, it was probably what took the most time of this whole build. 

Now was time for what I was most afraid of, the power supply, I saw some people saying that cabble managment is incredibly difficult in that case, and people said that with a modular PSU, and mine as NOT modular, and the 24 pin cable needed to be long enough to connect to the motherboard mine was 350mm. So I just connected everything in.

Then was time to connect the SSDs via SATA to my motherboard (That I took off my home old home server lol)

### Choosing/Setup the OS

To install the OS I took the SSD Nvme off my home server, and put on my computer to install truenas because I though that my CPU didnt had integrated graphics. But for the OS I choose truenas SCALE, (Now i am using ubuntu server).

I tried connecting the home server to a monitor now knowing that it had integrated graphics, but just a black screen was showing up, my father thought it could be the RAM so he took one off and the server turned on.

Now it showed the american megatrends logo and said CPU fan error, so my father saw if the cpu cooler was in the right place and it wasnt, so he put it without moving, but the error kept showing up, I searched up and gemini said that I needed to go to the BIOS, and change like a option that was limiting my CPU fan to 200RPMs I am not sure, and it worked, I disabled secure boot and I booted to truenas Scale without having any errors.

## Conclusion

I liked the PC building experience, and I did this to learn about the hardware and the software.
