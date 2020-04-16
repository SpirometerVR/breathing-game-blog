---
title: "Week 6: Prototyping continued..."
date: 2020-03-06T11:00:00+01:00

tags: ['Prototyping', 'Mini Games']
author: "CHLA Team"
noSummary: true

resizeImages: false
---
The process of building out each mini game continues. This week we took the time to integrate the use of the custom Digital Spirometer into or Unity projects. WIth the help of [__Unity OSC__](https://thomasfredericks.github.io/UnityOSC/) script, a headache and a lot of "Why is this not working!" our team finally found success. We now can use our inhalations on the digital spirometer to propel the boat forward in the scene of the Treasure Hunter game! In Addition to this, we also successfully pushed and tested the scene on the Oculus Go.

**Pain points**

We are finding the digital spirometer is not perfect. We are seeing that when it comes to getting the device working with Unity it has only worked thus far on macOS and not on Windows for our team. Also using the Arduino IDE to upload the `M5_Spirometer_2020.ino` script to the M5Stick-C works for some of our laptops, and not for others. During upload we are seeing the screen of the M5Stick-C keep flashing off and on for several times before the IDE throws an error.

{{< figure src="img/wifi_network.jpeg" >}}

**Next up...**

Next we will attempt to get the spirometer also intergrated into the Fruit Fall mini game, and attempt to get the prior teams Save the Village game fully working again. Currently we are unable to use the Oculus controller to begin the game and we still need to test it with the digital spirometer input.



-- The CHLA Team


