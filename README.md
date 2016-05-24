# Springboard in a Browser

for a personnal webapp, to minimise bouton on the screen, i would like to reproduce a part of ios springboard behavior: deleting an app.
I need the ability to select an icon, and use double tap on each icon to have infos.

deletion of app.-
-**LONG PRESS** to enter in 'jiggle Mode'
-**TAP** for delete icon
-**TAP** on background to stop 'jiggle Mode'

You can select an icon to (TAP on icon)

I've tested hammerjs lib to detect tap, doubletap and long press on touch device.
I've got an issue on mobilebrowsers (chrome android/ios, safari ios, firefox ios) with the TAP to exit 'jiggle Mode'.
It works fine until you delete an icon. therefor impossible to exit 'jiggle mode', Background Tap listener does not fire any more.
