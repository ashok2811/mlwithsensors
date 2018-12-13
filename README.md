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
  * Open the preferences window from the Arduino IDE. Go to File > Preferences  
  * Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into Additional Board Manager URLs field and click the “OK” button  
  * Open boards manager. Go to Tools > Board > Boards Manager…  
  * Scroll down, select the ESP8266 board menu and install “ESP8266 platform”
* Select Board as Generic ESP8266 and Upload the esp.ino file to the ESP  
*Connections*    
 Tx - Tx  
 Rx - Rx  
 VCC- 5V  
 GND - 0V   
 GPIO0 -0V  
 CH_PD - 5V    
 Arduino Reset- Arduino GND   

* Once uploaded,disconnect your Arduino Board.  

* Remove Arduino Reset from Ground.  

####  Step 2 >> Making your sensor ready.   
![alt text](https://github.com/ashok2811/mlwithsensors/blob/master/mpu_nan0.jpg)  
*Connections*   
 SCL - A5  
 SDA - A4  
 INT - D2  
 VCC- 5V  
 GND - 0V 
 
 * Copy I2Cdev and MPU6050 to your Arduino's libraries folder and restart the IDE.  
 * Open the Arduino IDE and got to **Examples>MPU6050>MPU6050_DMP6**
 * Upload this file to Arduino Nano and check on serial monitor if MPU is giving the data.
 * Connect the ESP8266 according to following connections.  
 *Connections*   
 Tx - Rx  
 Rx - Tx  
 VCC- 5V  
 GND - 0V   
 GPIO0 -open  
 GPIO1 - open  
 CH_PD - 5V    

####  Step 3 >> Send data to UDP Server.  

####  Step 4 >> Save the incoming data. *(server side)*  

####  Step 5 >> View Data.  

####  Step 6 >> Filtering and Trimming the Data.  

####  Step 7 >> Feature Extraction and Labelling.  

####  Step 8 >> Training your Classifier and exporting the Model.  

####  Step 9 >> Realtime Predictions.  



