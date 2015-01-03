---
layout: default
---

## FAQ about Scrap

### How to install?

Our application "Scrap" is available on [Windows Phone Apps Store](http://www.windowsphone.com/en-us/store/app/scrap/896b0e1b-2c1a-40e4-9c55-09050e3860dc).

Windows Phone 8.0 and 8.1 are supported.

### How to use?
1. Launch remote control mode on your camera device.
  + Camera Apps models (E-mount, RX100M3 etc.): Launch "Smart Remote Control" app from application menu
  + Action cam, QX series: Turn Wi-Fi on
  + Others: Launch "Control with Smartphone" from menu
2. Connect your phone and camera from Wi-Fi setting of your phone
  + Note that your camera will appear on the access point list as "DIRECT-********:HDR-AS30V".
3. Launch Scrap app on your phone.

### Wi-Fi is connected, but it doesn't work well
**First of all, please update your camera's firmware or Smart Remote Control application to the LATEST one.**

In some models, shipping version software does not support remote control by 3rd party applications, even if it is listed as supported device.

- Camera Apps models requires install of Smart Remote Control app at PlayMemories Camera Apps store from your camera or PC.
Note that **almost all of pre-installed app are incompatible with Scrap**.
- QX10/100 and AS15 requires firmware update from your PC.

Unfortunately, some models **cannot be supported** because of API restriction of camera device.
On those devices, it seems that only Sony's official application can access API.
The followings are well-known incompatible camera devices

- RX100M2
- HX50
- WX80, WX200, WX300 

### How to transfer photos or movies from camera?
About photos,

- Currently, our application supports very limited models (AZ1, QX30, and QX1).
- For the other models, please try DLNA client apps published on the App Store.
It seems that some of DLNA control point application can fetch contents from Sony's camera devices.

About movies

- Transferring movie is hard to implement because saving movie to phone's storage is not supported on Windows Phone.

### NFC does not work

Make sure the followings:

- NFC setting of phone device.
- NFC setting of camera device. (Is NFC icon (like "N" character) displayed on the screen?)

### Too few functions
**Please update your camera's firmware or Smart Remote Control application to the LATEST one.**

If you're already using the latest one, what you are seeing on this application is what your camera device provide.
[See Sony's official documentation.](https://developer.sony.com/develop/cameras/)

### Too low framerate
It might be caused by phone's CPU performance.
Please try to turn off histogram display.

### Feedback
We're waiting your feedback on Twitter ([@scrap_support](https://twitter.com/scrap_support)).
Give us feedback and ask us anything!

And if you are a developer, share us on [the repository](https://github.com/locana/wppmm) directry.

---
[Back to Index](/)

