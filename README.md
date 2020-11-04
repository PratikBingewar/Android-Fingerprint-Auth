#Fingerprint authentication has been a huge leap towards a better user experience in smartphones. 

Having this golden feature in your user’s phone and trying to integrate this feature in your applications to increase security and the bonus of better user experience is worth a shot. Let’s see how we can quickly integrate a simple FingerPrint authentication into an android app.
While integrating Fingerprint auth in our applications, we need to take care of quite a lot of things concerning the hardware of the device our users are using. We know that only devices running android Marshmallow and above have support for Fingerprint scanners. Additionally to use the Android’s built-in Fingerprint features the user needs to have enabled fingerprint security in the device and have at least one fingerprint registered in the device. 
Let’s keep these points in mind and we need to check these things before dispatching a listener for fingerprint authentication.



