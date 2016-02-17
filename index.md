---
layout: default
---

## About

**Locana** and **Scrap** are Windows/Windows Phone applications to control
[Sony Camera Remote API](http://developer.sony.com/develop/cameras/) powered camera devices.

---

## Locana

New generation of remote control application for Sony camera devices.

Locana will follow the latest API and have new functions which will be supported on the new models.

### Windows 10 Universal Application

See [Locana for Windows 10](/win10_uwp.html)

### Windows Phone 8.1 Application

[Available on the store](https://www.microsoft.com/en-us/store/apps/locana/9nblggh2t6h1).

### Supported devices and applications

For detail, see official documents. [https://developer.sony.com/develop/cameras/](https://developer.sony.com/develop/cameras/)

- DSC-QX10 / QX100 (Firmware v3.00 or later is recommended)
- ILCE-QX1 / DSC-QX30
- HDR-AS15 (Only the latest firmware)
- HDR-AS20 / AS30 / AS100 / AZ1 / AS200
- FDR-X1000
- PlayMemories Camera Apps - Smart Remote Control v2.0 or later
    - A6000 / A5100 / A5000 / NEX-6 / NEX-5R / NEX-5T
    - A7S / A7SM2 / A7R/ A7RM2 / A7 / A7M2
    - DSC-RX100M4 / RX100M3 / RX10M2
    - DSC-HX60 / HX90 / HX400 / WX500 etc.
- HDR-MV1

**Other old models cannot be supported by our application due to restricted API access.**

### Supported features

Available functions are based on provided APIs by each camera device (or installed Smart Remote Control app version).

Refer to the [official site](http://developer.sony.com/develop/cameras/) for details.

Additionally, Locana supports the following features.

- **Camera storage access for legacy models**
- Receive captured image and save to camera roll
- Video files download
- Sync pictures triggered by camera shutter key
- Geo-tagging
- RGB histogram
- Composition assist lines
- Wi-Fi connection assistant with NFC

### FAQ

See [Locana's FAQ](/locana_faq.html)

#### Development

Almost all of source code and assets are in the public repositories of our organization.

- [locana](https://github.com/locana/locana) for Windows 10.
- [uwpmm](https://github.com/locana/uwpmm) for Windows Phone 8.1.

***

## Scrap

Remote controlling application for Sony camera devices.
Scrap supports all of available functions.
Find it on the store for your Windows Phone 8.0/8.1 devices.

**Scrap will no longer be maintained because we're now working for a new universal app, Locana.**

### FAQ
See [Scrap's FAQ](/scrap_faq.html)

### Supported devices and applications

For detail, see official documents. [https://developer.sony.com/develop/cameras/](https://developer.sony.com/develop/cameras/)

- DSC-QX10 / DSC-QX100 (Firmware v3.00 or later is recommended)
- QX1 / DSC-QX30
- HDR-AS15 (Only the latest firmware) / HDR-AS20 / HDR-AS30 / HDR-AS100 / HDR-AZ1
- PlayMemories Camera Apps - Smart Remote Control v2.0 or later
  + A6000 / A5100 / A5000 / A7R / A7 / A7M2 / A7S / NEX-6 / NEX-5R / NEX-5T
  + DSC-RX100M3 / DSC-HX60V / DSC-HX400V etc.
- HDR-MV1

**Other old models cannot be supported by our application due to restricted API access.**

### Supported features

Available functions are based on provided APIs by each camera device (or installed Smart Remote Control app version).

Refer to [official site](http://developer.sony.com/develop/cameras/) for the details.

Additionally, Scrap supports the following features.

- Receive captured image and save to camera roll
- Sync pictures triggered by camera shutter key
- Geo-tagging
- RGB histogram
- Composition assist lines
- Wi-Fi connection support by NFC

#### Development

It had been developed on [this repository](https://github.com/locana/wppmm).
