# AIR-BERT  
**Fixed-wing RC aircraft**  

AIR-BERT is a self-designed remote-controlled aircraft.  
The first milestone is to build a fully functional airplane with agile flight characteristics.  
After achieving this, the next step will be to integrate a custom flight controller and develop a telemetry station to control and plan the aircraft’s missions.  

---

## Structure – Overview in Inventor (in progress)  
<img src="https://github.com/user-attachments/assets/9e9aa989-353d-4fec-9c0d-4f718a2e0ea7" width="60%" />
<img src="https://github.com/user-attachments/assets/6cd21d21-84d0-4713-929e-bef5c2ea65ff" width="60%" />



The airframe will be manufactured using lightweight PLA to ensure low mass and high stiffness.  

---

## Hardware  

- Servos (4x) 
- ESC (Electronic Speed Controller)  
- Brushless DC motor (BLDC)  
- LiPo 3S 5500 mAh battery  
- Flight controller (ESP32, MPU6050, BMP280)

<img src="https://github.com/user-attachments/assets/c47bbf67-b611-4c7a-b064-fa22d3f69cf1" width="60%"  />


---

## Flight Controller (planned)  

The flight controller will build on the experience from the HUBERT software project and the Mini ESP32 Drone:  
--> [fynnal98/HUBERT](https://github.com/fynnal98/HUBERT)  
--> [fynnal98/HUBERT](https://github.com/fynnal98/ESP32-Drone)

Future goals:  
- Stabilization (PID)  
- Sensor integration (IMU, barometer, 2,4Ghz modul)  
- Telemetry link with for mission planning (Ground Station)  
- Safety features (failsafe, heartbeat system)
- Logging  
