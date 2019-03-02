# Test_code_for_nrf24l01
Arduino test code for nrf24l01
The range of these sensors os drastiacally affected by the voalage spikes occuring between Vcc and ground.
Make sure that you solder a capacitor between vcc and ground pins of your sensors. This will increase the range of operation of your sensors from a couple of inches to 10-50 meters depending on the area you are in (RF signal becomes weaker depending on the no. of walls around you).

Generally no. specific value of capacitor is suggested, you can just scavenge electrolytic capacitors from dead electronics lying around your house. Anything between 10 to 100 micro farads / 5 - 25 V will work just fine


pin outs and illustrations are included in the folder
