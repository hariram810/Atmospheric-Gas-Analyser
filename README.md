# Atmospheric-Gas-Analyser

![Screenshot (630)](https://user-images.githubusercontent.com/118633170/205503777-44152762-f32a-4916-ab4d-ad065ca60138.png)


If you have hard-time 3d printing stuff and other materials which i have provided in this project please refer the professionals for the help, [JLCPCB](https://jlcpcb.com/RNA) is one of the best company from shenzhen china they provide, PCB manufacturing, PCBA and 3D printing services to people in need, they provide good quality products in all sectors

[JLCPCB](https://jlcpcb.com/RNA)


Please use the following link to register an account in [JLCPCB](https://jlcpcb.com/RNA)

https://jlcpcb.com/RNA


Pcb Manufacturing

----------

2 layers

4 layers

6 layers

jlcpcb.com/RNA



PCBA Services

[JLCPCB](https://jlcpcb.com/RNA) have 350k+ Components In-stock. You don’t have to worry about parts sourcing, this helps you to save time and hassle, also keeps your costs down.

Moreover, you can pre-order parts and hold the inventory at [JLCPCB](https://jlcpcb.com/RNA), giving you peace-of-mind that you won't run into any last minute part shortages. jlcpcb.com/RNA



3d printing

-------------------

SLA -- MJF --SLM -- FDM -- & SLS. easy order and fast shipping makes [JLCPCB](https://jlcpcb.com/RNA) better companion among other manufactures try out [JLCPCB](https://jlcpcb.com/RNA) 3D Printing servies

[JLCPCB](https://jlcpcb.com/RNA) 3D Printing starts at $1 &Get $54 Coupons for new users

This Is An AtmosphericGasAnanlyser Using MQ Series Sensors, Dht-11 Sensor & Arduino The Basic Idea Is To Precisely Measure Data Using Sensors Analog Read & Display It In I2CLcd, Here The Sensors Can Give Values Of LPG, CNG, HYDROGEN, AIR-QUALITY This Project Can Be Used To Collect Sensor Readings For FutureResearchProcesses. If You Need You Can Simply Add An SD Card To Store The Data As String And Collect The Readings, Here For Simplicity & SpaceReduction Iam Using Arduino Nano And I2ClCD Display, For My Ease. The Sensors Spit Out Aanalog Readings And I Have Converted It Into Useful PPM Values Of The Sensors analogToPPM(analogRead(The Sensor)). It Is Very Useful So I Have Converted It To PPM,

![Screenshot (640)](https://user-images.githubusercontent.com/118633170/205503788-ca3b0dc1-6ab0-438e-97f4-15271b4ecdb3.png)

![Screenshot (641)](https://user-images.githubusercontent.com/118633170/205503796-d28fe61a-0457-4b5a-a38e-bc131afa4916.png)


Connecting the hardware and Reading the analog value is easy, but the most difficult thing is to calibrate the sensors and calculating the ppm(parts per million) value for a specific gas. After searching for a long time on the internet, I find a library for those sensors. And comparing the calculation with the datasheet of the sensors, it seems promising.

![Screenshot (644)](https://user-images.githubusercontent.com/118633170/205503802-43ec9061-93da-46b0-aa0c-6a03efcbb62b.png)


Here I found an article that explains the working and the calculation for an MQ sensor- UNDERSTANDING A GAS SENSOR.

I use the library and write a code to use six of those sensors with an Arduino nano and show different gas concentrations on air.

You can find the library here - MQUnifiedsensor library
