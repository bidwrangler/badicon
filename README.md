# Based on the Phonegap Hello World template

## Usage

Install the push plugin

    phonegap plugin add phonegap-plugin-push --variable SENDER_ID=XXX

Do a build and run it on the emulator

    phonegap run ios --target "iPhone-6-Plus" --emulator

## Phonegap Build

Do a build on build.phonegap.com and install the app on an iPhone 6 Plus (running 9.3.1)... Launch the app which will ask if you're ok with Notification.  Say yes, and then go to the Settings.  The icon showing for "Bad Icon" should be the Cordova icon instead of the one included in this package.
