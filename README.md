# Arduino Bluetooth Car

### Material required:

Ardrino uno : https://amzn.to/2HOy5T1

Motor driver :  https://amzn.to/2UE5mSl

4 Dc motor : https://amzn.to/2HLGsP7

Bluetooth HC 05 : https://amzn.to/2TuSu0D

Car Chessie and tyres :  you can get it from offline online it will be really costly

___________________

## Wiring Digram-

### Bluetooth - arduino 

TX to rx 

Rx to tx

Ground to ground

3.3 V to 3.3 V

____________________

### Motor driver  - arduino 

Pin 1 to 9 

Pin 2 to 10

Pin 3 to 11

Pin 4 to 12

12 v to battery 

Ground to batery Ground

### App to use to control
https://play.google.com/store/apps/details?id=braulio.calle.bluetoothRCcontroller


# video Demo
[![](http://img.youtube.com/vi/cdf8Cy0FDx8/0.jpg)](http://www.youtube.com/watch?v=cdf8Cy0FDx8 "")

Step 1: Assemble the circuit as shown in the schematic given below. You can use the battery pack for powering driver circuit which I have mentioned in the components section or you could try out some other battery pack, but keep it mind it should deliver between 7-12V and atleast 3500mAh. Also, use different battery/battery-packs for powering Arduino and the Motor-Driver module, but ensure they share a common ground. Battery is one of the most important thing in this project !
Step 2: Compile the code given below in the Arduino-IDE and hit upload, but before that make sure you have disconnected RX of Arduino from TX of Bluetooth Module (HC-05).
Step 3: Install the application on your Android device through a link provided below.
Step 4: Pair your Android device and HC-05 over Bluetooth. Now, open the app and click on Bluetooth-icon and select your device from the list.
Step 5: Now you have gone through all the hard work ! Just sit back and relax and use the on-screen controls available on the app to control the car/bot. You could also change the schematic and code, and add some servos or other actuators to it. But keep it mind as you increase the quantity of actuators, your car/bot would demand more power from the battery/battery-pack
