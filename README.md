Chromium v35 (64bit) - debian_flashplayer v.14        
==================



1. download the player.so and put it in the browser's plugin directory ( /usr/lib/chromium/plugins/)

2. add a flag in /etc/chromium/default
   --ppapi-flash-path=/usr/lib/chromium/plugins/player.so 

3. start chromium
