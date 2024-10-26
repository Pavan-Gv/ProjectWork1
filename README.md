## TOXIC GAS LEAK DETECTION & ALERTING DEVICE: 
The development of a toxic gas leak detection and alert device using IoT and machine learning focuses on enhancing safety by providing an affordable and efficient solution. This project aims to create a standalone system capable of detecting harmful gas leaks through the integration of an ESP8266 module, MQ-135 gas sensor, and a machine learning-based RFR algorithm. The system will process sensor data to reliably identify gas leaks and promptly alert individuals in the vicinity, ensuring timely response and increased safety.

## About
<!--Detailed Description about the project-->

In response to the imminent threat of toxic gas leaks, this project addresses the limitations of conventional detection methods by developing an advanced Toxic Gas Leak Detection and Alert System. Leveraging IoT and ML, the system monitors gas concentration, temperature, and humidity using DHT11 and MQ135 sensors. Through real-time analysis and alerts via SMS and email, the aim is to enhance early detection capabilities, ensuring prompt and effective responses to mitigate potential hazards. Harmful gas leakage is a serious safety hazard. Current gas detection systems are often expensive, complex, and require regular maintenance. This project aims to develop a low-cost, easy-to-deploy, and reliable system for detecting harmful gas leakage without connecting to other devices. The system will use an ESP8266 module, MQ-135 gas sensor, and RFR algorithm to collect and analyze data from the gas sensor to detect harmful gases and send alerts to the people in the surroundings.

## Features
<!--List the features of the project as shown below-->
Prevention of accidents : 
The main purpose of this project is to develop a system that can detect harmful gas leakage early and warn people in the surroundings, so that accidents can be prevented. 
Sensors Integration:
The system will use sensors to detect harmful gases. Sensors are devices that can detect changes in the environment, such as temperature, pressure, and gas concentration. The MQ-135 gas sensor is a type of sensor that can detect a variety of harmful gases, including carbon monoxide, methane.
Cost Effectiveness :
The system will be low-cost to deploy and maintain. This is important because it will make the system accessible to a wider range of people and organizations. The low cost of the system will also make it more attractive to businesses and governments.

## Requirements
<!--List the requirements of the project as shown below-->
```
-> Determining the data regarding the gases level those are above threshold.
-> Setting up the Hardware Requirements:
      -> ESP8266 module,
      -> MQ-135 gas sensor,
      -> Connecting Wires &
      -> Breadboard  
-> Programming the ESP32 Module using Arduino IDE which can collect the data from sensor and send that data to an API.
-> Connecting to an API to store data for processing and Sending Alerts through Mail and Mobile Numbers.
-> Pushing the data to a IOT platform such as BLYNK or THINGS SPEAK.

```

## System Architecture
<!--Embed the system architecture diagram as shown below-->
![image](https://github.com/user-attachments/assets/7f5d27bc-72fd-4bc3-a8e4-fa8e63c985fb)
![image](https://github.com/user-attachments/assets/c56a398e-ab4a-4a90-9b4a-f93d63774a33)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Values Updation in Blynk
![image](https://github.com/user-attachments/assets/4f5e9fd4-d746-4ad7-bf43-8b8eb25bd1c1)


#### Output2 - Terminal Live Updation
![image](https://github.com/user-attachments/assets/1ea63ea6-f675-449a-9b8e-d7a4ce1e855f)

![image](https://github.com/user-attachments/assets/62fbfea7-0f18-4871-a9ea-75c4eda2c147)

### Output3 - Algorithm Output
![image](https://github.com/user-attachments/assets/5885abae-f99c-420d-943b-a2079b12bddc)

## Results and Impact
<!--Give the results and impact as shown below-->
	The project successfully addresses the limitations of traditional gas detection methods by combining cutting-edge technologies. The seamless integration of IoT devices, machine learning algorithms, and cloud-based communication platforms contributes to a robust and responsive detection and alerting system. The flexibility of the system allows for easy deployment in diverse environments, enhancing public safety and environmental monitoring. 

	As technology advances, the future direction of this project could involve further exploration of advanced machine learning techniques, such as deep learning, for even more precise toxicity predictions. Additionally, expanding the range of monitored gases and incorporating additional environmental parameters would contribute to a more comprehensive safety solution. Overall, this project lays a solid foundation for the continued development of intelligent and proactive systems for toxic gas detection and emergency alerting. 


## Articles published / References
```
[1]  Dhanalaxmi, B., & Naidu, G. A. (2017, February). A survey on design and analysis of robust IoT architecture. In 2017 International Conference on Innovative Mechanisms for Industry Applications (ICIMIA) (pp. 375-378). IEEE.
 
[2]  Krishnamurthi, K., Thapa, S., Kothari, L., & Prakash, A. (2015). Arduino based weather monitoring system. International Journal of Engineering Research and General Science, 3(2),452-458. 

[3]  Sabharwal, N., Kumar, R., Thakur, A., & Sharma, J. (2014). A Low-Cost Zigbee Basedautomatic Wireless Weather Station With Gui And Web Hosting Facility. International Journal of Electrical and Electronics Engineering.
 
[4]  Mahmood, S. N., & Hasan, F. F. (2017). Design of weather monitoring system using Arduino based database implementation. Journal of Multidisciplinary Engineering Science and Technology (JMEST), 4(4), 7109. 
![image](https://github.com/user-attachments/assets/d8af4841-7922-4bd9-8909-153353ad27a8)
```


