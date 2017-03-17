# Contiki_6LoWPAN_CC2650_BBB
Application of Internet of Things using Contiki-based devices arranged in 6LoWPAN mesh WSN. The sensor data are forwarded to the cloud 
via a border router. Once the cloud receives the data, it visualizes the data in real-time. 

This work is an implementation of http://processors.wiki.ti.com/index.php/Cc26xx_sw_examples. A walkthrough on this implementation
is posted for documentation purposes as it might also help anyone who is working on it, especially since the TI tutorial
has not been updated for a while. The slides are posted to provide a brief review on the project's conceptual background.

Note that this work is done on Windows. SSH to BeagleBone Black is done using PuTTY.

Required hardware:
1. Texas Instruments CC2650 SensorTags 2.0 (http://www.ti.com/ww/en/wireless_connectivity/sensortag/)
2. Texas Instruments CC2531 USB dongle (http://www.ti.com/tool/CC2531EMK)
3. BeagleBone Black (http://beagleboard.org/black)
4. IPv6-supported access point

Additionally, we need the following software:
1. Texas Instruments SmartRF Flash Programmer
2. Texas Instruments SmartRF Flash Programmer 2

