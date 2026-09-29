## Hi, I'm Daniel Santiago Arcila Gómez 👋                                                                                                        
                                                                                                                                                      
**Electronics Engineer — Universidad de Antioquia (UdeA)**                                                                                     
Focused on **Embedded Systems, Real-Time Firmware & Low-Level Architecture**                                                                   
Expertise in **Microcontrollers (ESP32, RP2040, STM32), RTOS, Telemetry Protocols & Edge Systems                                             
                                                                                                                                                  
---                                                                                                                                               
                                                                                                                                                  
### Engineering Focus                                                                                                                          
                                                                                                                                                  
- **Deterministic Firmware:** C & C++ development for constrained targets, multi-core architecture, FreeRTOS, and zero-allocation critical loops. 
- **Hardware Interfacing & Buses:** Low-level driver design using DMA, PIO, RMT, I2S, SPI, I2C, and UART.                                         
- **Telemetry & Embedded Networking:** Binary packet protocol design, UDP streaming, REST endpoints, and low-latency wireless communication.      
- **Power & Safety Engineering:** Software-level current limiters, hardware protection, and thermal/power optimization.                           
- **Edge AI & Signal Processing:** Real-time digital signal processing (DSP), FFT analysis, and TinyML inference on resource-constrained microcontrollers.                                                                                                                                   
                                                                                                                                                  
---                                                                                                                                               
                                                                                                                                                      
### Featured Engineering Projects                                                                                                              
                                                                                                                                                  
#### **AURALUX — Dual-Core Real-Time Lighting & Audio Telemetry Platform**                                                                     
*Proprietary IoT & Embedded Firmware Architecture for ESP32-S3 (ESP-IDF v5)*                                                                      
- **Architecture:** Asymmetric dual-core workload distribution: Core 0 dedicated to networking (Wi-Fi, UDP streaming, REST API, ESP-NOW) and Core 
1 dedicated to a zero-allocation 144 Hz rendering engine.                                                                                           
- **Telemetry & Low Latency:** Custom 16-byte binary protocol streaming real-time DSP metrics via UDP (50 FPS) with sub-20ms system latency.      
- **Hardware Integration:** WS2812B/WS2815 driven via RMT peripheral, I2S digital MEMS microphone acquisition, and 2000 mA active power limiter   
for electrical safety.                                                                                                                              
- **System Reliability:** Dual-boot OTA firmware update system (`ota_0`/`ota_1`) with anti-rollback safety and Flash-protection debouncing.       
*(System architecture case study available upon request / in featured repositories)*                                                              
                                                                                                                                                  
#### 🔹 **Bare-Metal Preemptive RTOS (From Scratch)**                                                                                             
- Custom task scheduler, context switching in assembly, priority queues, and peripheral drivers developed without vendor SDKs.                    
                                                                                                                                                  
#### 🔹 **High-Speed Camera Acquisition System (Raspberry Pi Pico)**                                                                              
- Real-time video/image capture pipeline using RP2040 Programmable I/O (**PIO**) and multi-channel **DMA** offloading CPU core execution.         
                                                                                                                                                  
#### 🔹 **TinyML & Sensor DSP Engine**                                                                                                            
- On-device real-time inference, model quantization, and acoustic feature extraction for predictive analytics on edge nodes.                      
                                                                                                                                                      
---                                                                                                                                               
                                                                                                                                                      
### Tech Stack & Tools                                                                                                                         

**Languages & Firmware:**  
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00427E?style=flat&logo=cplusplus&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-4EAA25?style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Platforms & RTOS:**  
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=flat&logo=espressif&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-00878F?style=flat)
![ESP32-S3](https://img.shields.io/badge/ESP32--S3-000000?style=flat&logo=espressif&logoColor=white)
![RP2040](https://img.shields.io/badge/Raspberry%20Pi%20Pico-A22846?style=flat&logo=raspberrypi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Protocols & Peripherals:**  
`UART` • `SPI` • `I2C` • `I2S` • `DMA` • `PIO` • `RMT` • `UDP/TCP` • `OTA Dual-Boot` • `Wi-Fi / ESP-NOW`  

---

### 📬 Connect  

📧 **ds.arcilag@gmail.com**  
💼 [LinkedIn Profile](https://www.linkedin.com/in/daniel-santiago-arcila-g%C3%B3mez-2b8634206/)  
📍 Medellín, Colombia
