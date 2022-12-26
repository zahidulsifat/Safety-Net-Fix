# Safety-Net-Fix
The thing is you need to find a fingerprint value which supports safetynet pass and add it to your device build.prop.


DO REMEMBER THAT THIS REQUIRES MAGISK WITH MAGISK HIDE ENABLED.

THE BELOW METHOD REQUIRES MAGISK v14.0+

Open the build.prop file located in /system.Delete the previous fingerprint value in build.prop and
add the source code to the build.prop file.

Save and Exit.
Make sure you have enabled Magisk Hide in Magisk setings.
Reboot.

Important Notes

1. The fingerprint values need to be exactly the same. Any small change will trigger safetynet.

2. You can use any fingerprint value for your device. It's not necessary for you to take value specific to your device. As long as the fingerprint is valid, it will work.

3. This same trick will work on every Marshmallow and Nougat Roms

Added a screenshot as a proof that it's working.
Thank you!
