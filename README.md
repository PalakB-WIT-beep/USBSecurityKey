# USBSecurityKey

## The coding was done by Paul Mizzi and Palak Barua
## This is a project for our System Analysis and Design class

We wanted to make something that makes logging in to our devices faster and more secure. But we also didn't want to waste money on Security Keys when we had USB drives that could do the same thing with the right know how. We took some inspiration from programs like USB Raptor, which does the same thing. We also looked at companies like Yubico, which is the main provider of security keys, for ideas on how the firmware works and what security methods they use for their security keys. 

It sets up your USB to store a One Time Password (OTP) and then stores it on the key and the device you're connecting to alongside a public key. The OTP will be encrypted so that no one can figure it out (though we also have a reset option as a backup). The device will have a private key in order to de-encrypt the OTP and verify the key. 

This program will work via command prompt and will be available on Mac OS, Windows OS, and Ubuntu/Debian Linux distros. 

