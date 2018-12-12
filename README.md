# ML with Sensors
In this repo, I will teach you how to get started Machine Learning with your own sensors. Here we are sending data from a sensors to a server wirelessly. The server is processing the data and extrating meaning out of that data using Machine Learning.
####  Step 0 >> Componets you will need.  
Arduino *(here Arduino Nano)* , A Sensor *(here MPU6050)* , ESP8266-01
####  Step 1 >> Making your ESP ready to send the data. 
![alt text](https://github.com/ashok2811/mlwithsensors/blob/master/esp8266-5.png)

**Sending sensor data to UDP Server.**
* Upload a Bare Minimum Code for your Board.    
* Choose your board that you will be using to program your ESP. e.g Arduino Nano.  
* Download ESP8266 library & Board and add to the Arduino IDE.    
* Select Board as Generic ESP8266 and Upload the esp.ino file to the ESP  
*Connections*    
 Tx - Tx  
 Rx - Rx  
 VCC- 5V  
 GND - 0V   
 GPIO0 -0V  
 CH_PD - 5V    
 Arduino Reset- Arduino GND   

* Upload the esp.ino code.    

* Disconnect your Arduino Board, Make the Connection (Don't power now)  
*Connections*   
 Tx - Rx  
 Rx - Tx  
 VCC- 5V  
 GND - 0V   
 GPIO0 -open  
 CH_PD - 5V    
 Remove Arduino Reset from Ground.  

####  Step 2 >> Making your sensor ready.   
![alt text](https://github.com/ashok2811/mlwithsensors/blob/master/mpu_nao.jpg)


####  Step 3 >> Send data to UDP Server.  

####  Step 4 >> Save the incoming data. *(server side)*  

####  Step 5 >> View Data.  

####  Step 6 >> Filtering and Trimming the Data.  

####  Step 7 >> Feature Extraction and Labelling.  

####  Step 8 >> Training your Classifier and exporting the Model.  

####  Step 9 >> Realtime Predictions.  



