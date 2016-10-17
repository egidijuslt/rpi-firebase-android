# rpi-firebase-android
Connect your smartphone and IOT device 

First of all, you will have to create your firebase account which totally free of charge. Firebase is the only way to send push notifications to your android phone. Go to https://firebase.google.com/ click ‘’Get started for free’’ and follow the steps to initialize your firebase account. Remember you app ID!
Incorporate Android.txt code into your android app with your firebase app ID. This will update your smartphone token on firebase database every time it changes.
Use notification.py file in your raspberry pi or other controller to send a push notification to your smartphone.
