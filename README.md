# Child Safety Monitoring Android App


Designed and deployed an Android app for a Smart Bicycle to help parents monitor their child’s safety.

The smart bicycle has embedded hardware sensors and systems such as a Gyroscope, Accelerometer, GPS, Microphone, and Antenna. For this problem statement, assumed that Android mobile phone (Phone A)  behaves as the smart IoT embedded system and you are riding a (sensorless old-fashioned) bicycle. It should be able to transmit the data to your partner's device (parents’ Android mobile hereafter referred to as Phone B for warning.


The Child Monitoring Android app (during cycling) is able to do the following:

Continuously monitor the GPS, accelerometer, and gyroscope data of your phone to determine the following

  Over speed

  Fall detection

  Boundary crossing (define some geographical coordinates on campus)


If the cycle goes beyond a particular perimeter, or over speeds, the device does the following:

Play a beep alarm sound on your device (Phone A).
Display the real-time location of phone A on phone B using Google Maps and play a beep sound on Phone B.


If the cycle falls, the device does the following:

Play a beep alarm sound on the device (Phone A), with an option to switch OFF the alarm.
Display the real-time location of phone A on phone B using Google Maps and play a beep sound on Phone B.
If the alarm is not switched OFF within 5 seconds by Phone A,

a) Switch on the microphone and camera of phone A automatically and start recording.

b) Send an SOS from phone A to phone B by transmitting the recorded sound and images using mobile internet network. 

