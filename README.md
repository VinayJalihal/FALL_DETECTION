# FALL_DETECTION
IOT based fall detection system that alerts the family members about a fall occurred on a two wheeler bike
The device consists of an MPU6050 accelerometer and gyroscope sensor and a nodemcu
IFTTT applets are used to send the notifications
open IFTTT and click on create 
select webhooks for "if this"
note down the json url and unique webhooks privatekey
add a name for the applet
select rich notification for "then this"
give the message to be shown when fall occurs on the rich notification
paste the private key, url, mobile hotspot SSID and Password
upload the code to the board
