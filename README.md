# Arduino Bluetooth-Controlled Car

This repository provides all the required materials and instructions to build your very own Arduino Bluetooth car.

## Required Components

Here is the list of components you'll need for this project:

- Arduino Uno: Purchase [here](https://amzn.to/2HOy5T1)
- Motor Driver: Purchase [here](https://amzn.to/2UE5mSl)
- 4 DC Motors: Purchase [here](https://amzn.to/2HLGsP7)
- Bluetooth HC 05: Purchase [here](https://amzn.to/2TuSu0D)
- Car Chassis and Tyres: These can be procured offline as purchasing online may be significantly costlier.

## Wiring Diagram

The wiring diagram for this project is detailed as follows:

**Bluetooth to Arduino:**
- TX to RX
- RX to TX
- Ground to Ground
- 3.3V to 3.3V

**Motor Driver to Arduino:**
- Pin 1 to Pin 9
- Pin 2 to Pin 10
- Pin 3 to Pin 11
- Pin 4 to Pin 12
- 12V to Battery
- Ground to Battery Ground

## Usage Instructions

Here's how you can get the Arduino Bluetooth Car up and running:

1. Clone this repository to your local machine.
2. Open the `robo_car.ino` file in the Arduino IDE. If you don't have Arduino IDE installed, you can download it from [here](https://www.arduino.cc/en/software).
3. Upload the code to your Arduino Uno board. Make sure the board is connected to your computer via a USB cable.
4. Once uploaded, disconnect the Arduino Uno from the computer and connect it to the battery.
5. Install the [Bluetooth RC Controller app](https://play.google.com/store/apps/details?id=braulio.calle.bluetoothRCcontroller) on your smartphone.
6. Pair your smartphone with the Bluetooth HC 05 module via the Bluetooth settings of your phone.
7. Open the Bluetooth RC Controller app and start controlling your Arduino Bluetooth Car.

## App for Control

For controlling the car, you can use the [Bluetooth RC Controller app](https://play.google.com/store/apps/details?id=braulio.calle.bluetoothRCcontroller) available on Google Play Store.

## Video Demonstration

You'll find a comprehensive video demonstration detailing the whole process (link to be added).

Enjoy building and controlling your very own Arduino Bluetooth car!
