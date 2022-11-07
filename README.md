# SmartThingsEdgeDrivers

If you don't want to read about my drama and just want the Edge driver for the Graywind Zigbee ZF31 motors, you can just click this link and install the driver: 
https://bestow-regional.api.smartthings.com/invite/r3MyLdaxOPjp

I recently spent $800 on two sets of Smart Shades from Graywind (https://www.graywindblinds.com/) and while the quality was good, their website isn't the most forthcoming when it comes to useful information. I originally ordered the AC32 hardwired Wi-Fi motors thinking they would support SmartThings since they have SmartThings plastered all over their site. After receiving them and trying to get them connected, I was told that I was wrong and needed to order a different motor for an additional $70. I was grateful that they allowed me to do this.

I eagerly awaited their arrival and installed them as soon as they arrived. Unfortunately, I could not follow their cryptic manual that was included. I again reached out to support, and they provided me with these very simple instructions:

1) Reset the motor. Page 39 (How to reset the motor): Press and hold the button on the motor until the shade jogs 4 times （back and forth is one jog）.

2) Pair the motor with the remote. Page 40 (How to re-pair with motor) : Press and hold the button on the motor until the shade jogs one time; then select a channel; finally press the "P" button at the back of the remote within 10 seconds, the shade will jog twice. Then press up/down button to check if the shade runs in the correct direction. If not, please hold the “stop” button and “heart” button together for 2s, the running direction will be corrected. If yes, please disregard it and go to set the limit position.

3) Set the top limit position. Page 36 ( How to set top limit position): Raise the shade to the top position you want, then hold "up arrow" button & "heart" button at the same time until the shade jogs twice. [If the shade moves by like 1cm only, please hold up button for 3s, then it will move continuously.]

4) Set the bottom limit position. Page 37 ( How to set bottom limit position): Lower the shade to the bottom position you want, then hold "down arrow" button & "heart" button at the same time until the shade jogs twice. [If the shade moves by like 1cm only, please hold down button for 3s, then it will move continuously.]

5. Connect to SmartThings: Hold the button on the motor until it jogs twice, then blue light will flash.

This was GOLD. I could now connect them to SmartThings.

Unfortunately, this was not the end of my journey. I discovered an issue with the default SmartThings Edge driver when the shade motor is reversed. Ugh.

Basically, my blinds opened when I clicked close and closed when I clicked open - EVERYTHING was reversed. 
To my surprise, they said NOTHING about this issue on their website. I didn't see it in the reviews either (which I will be fixing).

I contacted their customer support and was told the following:

"I really regret to tell you the shade's running direction is backwards on the bridge app. This is the default. You're not able to change it. " -Graywind Zoe

When asked if they intend to correct this issue, I was told the following:

"Our enginners don't have a plan to fix it for the time being" -Graywind Zoe

This was extremely disappointing from a company who on their website actually brags "R&D Never Stops". 

Their printed instructions were nearly impossible to understand, but Zoe was able to very clearly articulate the steps I needed to follow to get the shades at least pared with SmartThings, so I am thankful for that.

Anyway, if you learned the hard way of this issue and took to Google for help you are in luck! Just Install this driver and solve your problem once and for all.

https://bestow-regional.api.smartthings.com/invite/r3MyLdaxOPjp