DUAL AXIS SOLAR TRACKER

DESCRIPTION

In a world rapidly shifting towards sustainable energy, our project presents an intelligent solution to maximize solar power efficiency — the Dual Axis Solar Tracker using ESP32.
Unlike conventional solar panels that remain fixed and capture sunlight only at certain angles, this system dynamically follows the sun throughout the day. By continuously aligning the panel perpendicular to sunlight, it ensures maximum energy absorption from sunrise to sunset.
At the heart of this system lies the powerful ESP32, which acts as the brain of the operation. Using strategically placed Light Dependent Resistors (LDRs), the system senses the intensity and direction of sunlight in real time. The ESP32 processes this data and intelligently commands servo motors to adjust the panel’s position along both horizontal and vertical axes.
This dual-axis movement enables precise solar tracking, significantly enhancing energy output — up to 40% more efficiency compared to fixed systems.
![WhatsApp Image 2026-04-08 at 00 10 20](https://github.com/user-attachments/assets/cb68a2f0-ec68-4a8b-ade6-7060693461b6)


COMPONENTS USED

- ESP32  
- LDR Sensors (4)  
- Servo Motors (2)  
- Resistors  
- Solar Panel  
- Power Supply  


FEATURES

- Smart control using ESP32  
- Real-time sunlight tracking  
- Dual axis movement (horizontal & vertical)  
- Improved efficiency (~40%)  
- Eco-friendly solution  



WORKING

1. Sunlight falls on the LDR sensors placed around the solar panel.  
2. Each LDR senses light intensity and produces a voltage based on it.  
3. The ESP32 reads these values using its ADC pins.  
4. It compares the light intensity from different directions.  
5. If imbalance is detected, ESP32 sends PWM signals to servo motors.  
6. The servo motors rotate the panel horizontally and vertically.  
7. The panel aligns towards the direction of maximum sunlight.  
8. This process repeats continuously throughout the day.



 
<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/df886ec5-3de7-4c84-8119-ca76b0a988eb" />
 



 DEMO VIDEO
 
 https://drive.google.com/file/d/1LcjlcnVqPUfmlFSG5fc1pDEJjSLjp7CA/view?usp=drivesdk
 
 
Result
The system successfully tracks the sun in two axes and increases energy efficiency compared to fixed solar panels.


 
