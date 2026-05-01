# j-knight.github.io
Technical Blog


Initial Setup of Technical Blog
April 11, 2026

⦁	After a glancing at my platform options, I decided to go with Github pages to start my technical blog
     -	Figured I should sign-in to my github at this point.

⦁	A qucik google search and a click on “Quickstart” brought me to https://docs.github.com/en/pages/quickstart
     -	Made it tjrough to the last two steps before realising that it would probably be a good time to start documenting the process, so that I have something to use for the first blog entry. 
     -	But not before getting distracted by a short detour to check out the Jekyll themes. https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll

⦁	Documented everything up to this point before taking a look at the live site https://j-knight.github.io/ and deciding it definitely needed a visual theme. ![ImagePreview - Copy](https://github.com/user-attachments/assets/34914fcc-ded1-415e-b997-64967e5e0f71)
     - Considered using the github.dev code editor to customize the HTML layout and CSS, but decided to just start with one of the themes that were presented in the jekyll guide…

⦁	Setting up the blog with github pages has gone smoothly so far, for the most part, and it would be quick too, but it’s been difficult to stay on task without having to reel myself back in from distractions every two minutes. 
     -	Since I’ve finished with the initial set-up, I’m going to come back to this later when I won't be so easily distracted(hopefully).



Installing Kali Linux
April 15, 2026

⦁	 Decided I would install Kali Linux on my old PC instead of using my Raspberry pi with unbuntu already installed
     - I set up old pc. Wouldn’t turn on. Swapped IEC and outlets. PSU is likely dead. Will test later

⦁	Since my PSU on my old PC isn’t powering on and I don’t want to dual boot on my main PC, it looks like I’m installing on the pi
     - I haven’t touched it in a few years. PiOS ended up being too out of date to fully update with sudo apt update & upgrade. 
I alredy inteded on wiping the SD card with unbuntu on it. So I’m not bothering with that
Try using Pi Imager to write Kali to an SD card. Kept running into error for unmatching hash. Also, the imager version was outdated and wouldn’t update without doing some workarounds that I did not want to get into.

⦁	After trying for a while, I give in and install Pi Imager on my main PC.
     - I still run into the same error when using the imager.
     - At this point, I decide to re-install the PiOS with the imager onto the pi SD card.

⦁	Update the OS for the pi and tried again to install Kali Linux from the Pi Imager on the Pi.
     - Still running into the same issue with the hashes not matching.

⦁	I went to Kali’s website and downloaded the image file from there.
     -	Followed the steps listed at https://www.kali.org/docs/introduction/download-official-kali-linux-images/

⦁	After working on this all day, I eventually got it all set up. Honestly, hardware was a bigger issue. My wireless keyboard and headset kept interferring with each other and instead of turning the headset off, I just kept letting it get in the way. It all worked out well though.



Linux troubles
April 30, 2026

⦁	I got a new raspberry pi 5 to install and use linux on
⦁	Setup started out fine until I went to install openvpn for another class. I had previously installed it on Pi OS on a pi 4 without any issue
⦁	There was an issue with downloading the packages saying there was no support for aarch
⦁	I knew that the OS for the pi 4 was the most recent version based on debian(13) trixie
⦁	Decided to check the version for the pi 5. It was an older version of debian(12) bookworm
⦁	Loaded in the SD card that I was using for the Pi 4 so that I could wipe and write the current version of the OS onto the PI 5
⦁	After set up, I went to install openVPN and had no issues.
