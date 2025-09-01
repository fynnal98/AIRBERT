# AIR-BERT  
**Fixed-wing RC aircraft**  

AIR-BERT is a self-designed remote-controlled aircraft.  
The first milestone is to build a fully functional airplane with agile flight characteristics.  
After achieving this, the next step will be to integrate a custom flight controller and develop a telemetry station to control and plan the aircraft’s missions.  

---

## Structure – Overview in Inventor (in progress)  

<img src="https://github.com/user-attachments/assets/194cd20f-476d-4b67-8139-978ec74ecc51" width="48%" />  
<img src="https://github.com/user-attachments/assets/790f2e6d-2e4d-426c-9ab0-2fb4ddc7c1a0" width="48%" />  

The airframe will be manufactured using lightweight PLA to ensure low mass and high stiffness.  

---

## Hardware  

- Servos for control surfaces  
- ESC (Electronic Speed Controller)  
- Brushless DC motor (BLDC)  
- LiPo 3S 5500 mAh battery  
- Flight controller (ESP32, MPU6050, BMP280)  

---

## Flight Controller (planned)  

The flight controller will build on the experience from the HUBERT software project:  
--> [fynnal98/HUBERT](https://github.com/fynnal98/HUBERT)  

Future goals:  
- Stabilization (PID)  
- Sensor integration (IMU, barometer)  
- Telemetry link for mission planning (Ground Station)  
- Safety features (failsafe, heartbeat system)
- Logging  
