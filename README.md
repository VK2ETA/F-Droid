F-Droid personal repository

Contains the Android RadioMsg app together with its two companion apps, Where_is_it? which allows GPS position messages to be located on a compass together with distance and ETA, and QUIK-RMSG which is the replacement for the standard SMS/MMS Android app that allows RadioMsg to send and receive cellular messages and function as a cellular messages relay. 

Where_is_it? and QUIK-RMSG are optional apps. RadioMsg will function without them, just with reduced features:
   1. If QUIK-RMSG is not installed, the app can only relay over-the-air messages and messages to/from email addresses. When installed, and selected as the default messaging app, relaying to cellular SMS/MMS is enabled.
   2. If Where_is_it? is not installed, positions from GPS messages can be located in other apps like Google maps.

To install any of these apps, open F-Droid, go to Settings, click on Repositories, click on the + button and either enter the repository manually as https://vk2eta.github.io/F-Droid/repo
OR scan the QR code below.

To install the F-Droid app, go to their official site at https://f-droid.org/ and follow the instructions.

F-Droid is an app store dedicated to open source software. Its central repository contains many free open source apps for Android.

The source code of all my apps are on Github, and specifically for these three apps you can find them at:

RadioMsg and Where_is_it?:  https://github.com/VK2ETA/RadioMsg/releases

QUIK-RMSG: https://github.com/VK2ETA/quik-RadioMsg/releases

Attributions and great thanks to the developers of:

- QUIK, as QUIK-RMSG is a fork of that nice messaging app available in F-Droid and at https://github.com/quik-sms/quik/releases. QUIK-RMSG works the same as the original QUIK, it just adds the option for a secured access by RadioMsg to sending and receiving SMSs and MMSs. No other apps can have silent access to the messages as it requires the RadioMsg specific app signature.

- Getback-GPS, as Where_is_it? is a slightly modified version of that app relying on its nice compass graphics. The original is available in F-Droid and at https://github.com/ruleant/getback_gps/releases.
