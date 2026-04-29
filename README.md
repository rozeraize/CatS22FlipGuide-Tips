# CatS22FlipGuide-Tips
Tips for the Cat S22 Flip
# Fixing keypad.
The keypad starts to have sensativity issues after extended use. 
The issues can either be fixed by
1. downloading and installing [this apk](https://github.com/Qar-Kain/CatFix/releases/tag/v1.0.20032025) once your Cat S22 is rooted. (PS: choose the apk without bluetooth)
2. Or by following [this guide](https://www.ifixit.com/Guide/CAT+S22+Flip+Keypad+Replacement/199702)
# Quicker animations and smoother expierence
I find that removing animations speeds the phone up alot.
you can speed up or remove animations 2 ways:
1. To fully remove animations navigate to 'Settings>Accessability>Remove Animations' and enable 'Remove Animations'
2. If you still want animations but you want them to be faster then navigate to 'Settings>System>Developer Options' and there will be 3 diffrent animation options; 'Window animation scale', 'Transition animation scale', and 'Animator duration scale'. Each of those 3 options are set to 'animation scale 1x' by default. change the scale to .5x for each of the 3 options individually and try them out till you find which animation speed you like best for each.
# Device Navigation with keypad
1. To open app drawer on home screen with keypad double-press the home button.
2. To open quick-settings with keypad press and hold the recent apps button.
3. To speed dial on home screen press and hold any the numbers 1-9 on homescreen. It will ask you to assign a phone number for the key you pressed, and click yes and then assign a phone number. (key 1 is already assigned to voicemail)
4. To remove an apps from recents in the recent apps dailog press the 'UP' button and then press the C/Clear button to remove the app from recents.
# Debloating, Degoogling, Rooting. 
1. Follow [this guide](https://xdaforums.com/t/tut-root-how-to-root-cat-s22-flip-on-version-30.4626971/) to root your phone.
2. Afterwards, follow [this guide](https://forums.jtechforums.org/t/kitty-rom-small-cat-super-debloated-with-android-auto/) to install a custom debloated rom.
3. Once you installed the rom, setup the phone WITHOUT CONNECTING TO THE INTERNET.
4. Download the 'Magisk-V30.7.apk' from [here](https://github.com/topjohnwu/Magisk/releases/tag/v30.7).
5. Copy the apk from your computer onto your phone and install it.
6. Open the Magisk app and it will reboot your phone.
7. After magisk rebooted your phone, go back into the magisk app and go to the magisk settings.
8. Within the magisk settings press 'Systemless host' and enable zygisk and press 'enforce deny list'.
9. Exit the magisk settings and reboot your phone
10. I created A magisk module to debloat and degoogle your phone even more after you've already installed the kitty rom and rooted your phone. I created 2 versions of the magisk module. 1 version has google messages installed and the other version has the default andriod 11 messaging app installed. If you want google messaging download [this](https://github.com/rozeraize/CatS22FlipGuide-Tips/blob/main/degoogled-module/google-messaging.zip) zip file. If you want the plain android messaging app download [this](https://github.com/rozeraize/CatS22FlipGuide-Tips/blob/main/degoogled-module/non-google-messaging.zip) zip file.
12. copy the zip file you downloaded from step 10 onto your phone.
13. open the magisk app, navigate to the modules section, click 'install from storage', then choose the zip file that you downloaded.
14. After magisk installs the zip file as a module restart your phone.
15. NOW YOU CAN CONNECT YOUR PHONE TO THE INTERNET.
16. Download [this magisk module](https://github.com/Xenoxis/magisk-disable-logd/releases/tag/v1.0.1) and copy it and install it onto your phone for a slight performance boost.
17. Download [this magisk module](https://github.com/symbuzzer/Volte-Wifi-Calling-Enabler/releases) and install it onto your phone to enable volte wifi calling.
18. Download and install [this magisk modules](https://github.com/KOWX712/PlayIntegrityFix/releases).

