# Arduino-Based GPS Tracker

## Objective
To design and implement an Arduino-based GPS tracker capable of providing real-time location tracking via SMS commands.

## Methodology
- **Hardware Setup:** Utilized an Arduino board, SIM800 GSM module, and a GPS module for communication and location tracking.
  
- **Software Integration:** Integrated the TinyGPS++ library to decode GPS data into coordinates and used SoftwareSerial and AltSoftSerial libraries for communication between the Arduino and the SIM800 module.
  
- **Program Development:** Developed a program that reads SMS commands and sends the current location as a Google Maps link in response to the command, enabling easy real-time tracking.

## Results
- **Successful Tracking:** The GPS tracker was able to provide accurate real-time location data of the bicycle via SMS, demonstrating reliable performance and responsiveness to commands.

