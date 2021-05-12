# mid2

## How to run my code  
I have 3 RPC functions :  
### (1) wifi_f  
@ type "/wifi_f/run" to connect to the wifi  
@ but i didn't use MQTT to transfer data  

### (2) gc  
@ type "/gc/run" to call accelerator capture mode  
@ 3 gestures : "ring", "slope", "punch"  
@ my feature is to test if the y-direction has 60% over 1000  

### (3) plot  
@ type "/plot/run" to call the plot function  
@ there will be two plots  
@ the first is the type of gesture, 0 meeans ring, 1 means slope, 2 means punch  
@ the second is my feature, if the y-direction has 60% over 1000, it will be yes(O)  

## Screen shot
![image](https://github.com/Darowcat/hw2/blob/master/hw2_code/222149.jpg)
