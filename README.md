# cordova-plugin-AndroidAudioControls

AndroidAudioControls
=======

> The `AndroidAudioControls` object provides some functions to invoke and customize the Android Notification Audio Controls.


## Installation

    cordova plugin add cordova-plugin-AndroidAudioControls
  
Methods
-------
This plugin defines global `AndroidAudioControls` object.

Although in the global scope, it is not available until after the `deviceready` event.

    document.addEventListener("deviceready", onDeviceReady, false);
    function onDeviceReady() {
        console.log(AndroidAudioControls);
    }

- AndroidAudioControls.method()

Supported Platforms
-------------------
- Android

Other platforms either already have plugins, or don't require them. 
