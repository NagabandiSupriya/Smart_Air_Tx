# 🌬️ SMART Air Tx (Smart Air Transmitter System)

Smart Air Monitoring &amp; Transmission System using STM32F429, FreeRTOS, and DHT11 sensor. Real-time temperature &amp; humidity data acquisition with multitasking support.

A real-time embedded system project built using **STM32F429 microcontroller**, **FreeRTOS**, and **DHT11 sensor** to monitor and transmit environmental conditions like temperature and humidity.

## 🚀 Features

- 📡 Real-time air data monitoring (Temperature & Humidity)
   
- ⚙️ Multitasking using FreeRTOS
 
- 🌡️ DHT11 sensor integration
  
- ⏱️ Efficient task scheduling
  
- 🔄 Continuous data acquisition and processing
  

## 🛠️ Tech Stack

- **Microcontroller:** STM32F429ZIT6
- **IDE:** STM32CubeIDE
- **RTOS:** FreeRTOS
- **Sensor:** DHT11


## 🧩 Project Structure
SMART_Air_Tx/

│── Core/

│ ├── Inc/ # Header files

│ ├── Src/ # Source files

│── Debug/ # Build outputs

│── .ioc # STM32CubeMX configuration

│── FreeRTOSConfig.h

│── main.c

---

## ⚙️ How It Works

1. The **DHT11 sensor** reads temperature & humidity data.

2. FreeRTOS manages multiple tasks such as:
   - Sensor reading
    
   - Data processing
    
   - Transmission handling
    
4. Data is continuously updated and can be extended to IoT/cloud systems.

## 🧪 Key Learning Outcomes
- Real-time operating system (RTOS) concepts
 
- Task scheduling & synchronization
 
- Embedded system design

- Sensor interfacing

- STM32 HAL usage
