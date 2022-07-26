# Graco-Demo
This project demonstrates the music playing capabilities of Chimera as well as simple BLE data control.
Music is generated using PWM, currently in 8-bit mode with provisions for 16-bit.
The PWM signal is filtered with an 3rd order active low pass filter and then amplified with a small class D amplifier.
I am using an old Alexa Dot for the speaker since they sound good. Be sure to plug the speaker in before the USB cable!!
The Android App allows you to control Chimera using similar buttons as the Graco swing. 
  Press Speed Up and the Red LED will come on.
  Press Speed Down and the Red LED will go off.
  Press Volume Up and the Blue LED will come on.
  Press Volume Down and the Blue LED will go off.
  Press the Music button and music will play. If pressed while playing it will skip to the next song.
Currently there are three short song files but anything could be added here.

An Android App was created with MIT App Inventor and is included here as an APK file. 

The MIT App Inventor source is also included as an AIA file.

The MPLABX project files are in the ZIP file.

![Android App Screenshot (Small)](https://user-images.githubusercontent.com/57275578/179342346-aace95ce-b875-411d-9471-fe88b61cfe02.jpg)
