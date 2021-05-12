First, "cd ~/ee2405/Exam2/test", change the ip address and wifi hotspot, and "sudo mbed compile --source . --source ~/ee2405/mbed-os/ -m B_L4S5I_IOT01A -t GCC_ARM --profile tflite.json -f" to compile.

Second, "sudo screen /dev/ttyACM0" to open screen and open another terminal to final_code and then "sudo python3 wifi_mqtt/mqtt_client.py".

Third, after the set finish, input "/ACC/run s" to start, move B_L4S5I_IOT01A in 1 minute and the gesture will generate, and ID, some event, feature will show on python 

Fourth, the python will terminate ACC mode so you can do third again.

Note1: gesture is not sensitive, the ring will appear many times, so you may not get slope and line easily. 
Note2: if you do nothing in screen too long, it may be no react, please restart from second step.
