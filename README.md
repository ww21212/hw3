# hw3
(1) how to setup and run your program 

    Prepare a PC to connected with B_L4S5I_IOT01A.
    Connect uLCD displayer to B_L4S5I_IOT01A, correctly.


(2) what are the results
    
    step1: Open screen to check the WIFI state.
![](https://i.imgur.com/1LqRkCz.jpg)
![](https://i.imgur.com/z19lHVb.jpg)

    step2: run the python code(hw3.py) to check B_L4S5I_IOT01A can pass information to PC by using WIFI/MQTT. 
![](https://i.imgur.com/AZ32ZCO.jpg)

    step3: Type "/mode_sl/run 1" to command B_L4S5I_IOT01A entering G_UI mode.

    Note: LED1 is turned on, if the device is in G_UI mode.
![](https://i.imgur.com/2sh5kOY.jpg)
    
    step4: Use gesture to change the value of angle threshold.
![](https://i.imgur.com/NMg5Vhx.jpg)
![](https://i.imgur.com/upSy0i1.jpg)
![](https://i.imgur.com/IDZhsCt.jpg)
![](https://i.imgur.com/h9Kf6Oo.jpg)

    step5: Press USER_BUTTON to confirm the angle threshold and then PC will command B_L4S5I_IOT01A existing current mode by typing "/mode_sl/run 3".
![](https://i.imgur.com/nDP6yDq.jpg)

    step6: Type "/mode_sl/run 2" to command B_L4S5I_IOT01A entering Tilt_Angle_Detection mode.

    Note: If the tilt angle is between 0~5 degree LED3 will blink to indicate user to tilt the device.
    Note: If the device is in Tilt_Angle_Detection mode, LED2 is be turned on.
    
![](https://i.imgur.com/zrjI37n.jpg)
![](https://i.imgur.com/V3yQ3Tt.jpg)


    step7: Tilt the B_L4S5I_IOT01A by the angle over the threshold 5 times, B_L4S5I_IOT01A will pass information by WIFI/MQTT in the same time. Then PC will command B_L4S5I_IOT01A existing current mode by typing "/mode_sl/run 3".
![](https://i.imgur.com/9FL58Fb.jpg)
![](https://i.imgur.com/rCmTKr3.jpg)
