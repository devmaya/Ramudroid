
![alt Ramudroid ](https://altanaitelecom.files.wordpress.com/2016/03/ramudroid-image.png?w=500)

[![Gitter](https://badges.gitter.im/altanai/m2mcommunication.svg)](https://gitter.im/altanai/m2mcommunication?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Ramudroid is a bot to clean roads and outdoor environments. It is battery-powered. For brains, there's a Raspberry Pi on board. It's got wireless connectivity. There's a camera for real-time image sensing of the environment

Following are the resuable compoenets of this project :

# m2mcommunication
Communication between the web client , mobile client , cloud server , robots and other control points is primarily on REST over Internet or Wifi. For the mobile clients in vicinity if the robot they may even connevt via BLE ( blue tooth low enery ).

## Live streaming and image analysis
![alt Ramudroid v6.5] (http://s20.postimg.org/cf0t9nnkt/live_Streaming_1.png)

##Rpi core control unit
![alt Ramudroid v6.5] (http://s32.postimg.org/tkx97ih9x/Ramudroid_blacknwhite.jpg)

##Web Console for Ramu Droid
![alt web console ] (http://s32.postimg.org/xroj6320l/Ramudroidwebconsole.jpg)

##Wiring Pi
GPIO access library written in C for the BCM2835 used in the Raspberry Pi

> git clone git://git.drogon.net/wiringPi
> cd wiringPi
> git pull origin
> cd wiringPi
> ./build
> gpio -v
> gpio readall
