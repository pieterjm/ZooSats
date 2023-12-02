# DeviceTimer
**LNbits extension compatible with bitcoinSwitch device for timed triggering.**

Preview:

![combined_DeviceTimer_presentation_with_shadows](https://github.com/DoktorShift/DeviceTimer/assets/106493492/4bb2c7c1-a094-411e-9e98-f877ced08838)



This extension behaves like the standard LNURLdevice extension with the following changes:

**(1)** Payments available during specified time window. This allows to create a device (for animal feeding or whatever you want to activate) with opening hours so that it is only accessible during a specific time window.

**(2)** Timeout after each payment. After each succesful payment, the device is blocked for some time. This to prevent overfeeding or triggering when feeding is active.

**(3)** When making a payment is not allowed, an alternative image is displayed instead of a QR code. The LNURL payment flow also returns an error when trying to make a payment outside opening hours.

**(4)** Removed support for devices other that bitcoinSwitch



This LNbits extension was built with <a href="https://Business-Bitcoin.de">Business-Bitcoin.de</a> and massive support of <a href="https://github.com/pieterjm">Pieterjm</a>. Thanks Pieter!



