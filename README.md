# ALCOHOL_DETECTOR

# 🚨 Industrial Safety Monitoring & Workplace Alcohol Detection System

## 🎯 Problem Statement

🏭 Modern industries operate heavy machinery, automated production lines, CNC machines, robotic systems, and high-power electrical equipment. The operation of such equipment by an intoxicated worker can lead to ⚠️ workplace accidents, equipment damage, production losses, and serious safety hazards.

👷 Current safety monitoring methods rely heavily on manual supervision and security personnel, which cannot guarantee real-time detection and immediate preventive action. There is a need for an intelligent safety system capable of detecting alcohol consumption, preventing unsafe machine operation, and instantly notifying responsible authorities.

---

## 💡 Project Theme

### 🌐 Industrial IoT-Based Workplace Safety & Machine Access Control System

---

## 🎯 Project Objective

To develop a smart industrial safety controller using the **PIC16F877A Microcontroller** that can:

✅ Detect alcohol presence using an MQ3 sensor
✅ Monitor worker safety conditions in real time
✅ Automatically disable machine operation using relay control
✅ Generate audible alerts through a buzzer
✅ Display system status on an OLED display
✅ Send instant notifications through GSM communication
✅ Support industrial communication through RS485 networking

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚙️ Proposed Solution

The proposed system continuously monitors alcohol concentration levels using an MQ3 alcohol sensor connected to the PIC16F877A microcontroller.

### 🔄 Working Flow

```text
👷 Worker Breath Sample
          ↓
🍺 MQ3 Alcohol Detection
          ↓
🧠 PIC16F877A Processing
          ↓
📊 OLED Status Display
          ↓
🚨 Buzzer Alert
          ↓
🔌 Machine Shutdown (Relay)
          ↓
📱 Instant GSM Notification
```

When the measured alcohol concentration exceeds the predefined safety threshold:

🚨 Alarm is activated
🔌 Machine power is disconnected
📱 SMS alert is transmitted instantly
📟 Warning status is displayed on OLED

---

## 🔧 Technical Features

🔹 PIC16F877A Industrial Controller
🔹 MQ3 Alcohol Detection Sensor
🔹 SIM800L GSM Communication Module
🔹 SN65HVD3082E RS485 Communication Interface
🔹 OLED Monitoring Display
🔹 Relay-Based Machine Interlock System
🔹 Real-Time Safety Monitoring
🔹 ICSP Programming Support
🔹 Compact Custom PCB Design


---

## 🌟 Key Innovation

Unlike conventional alcohol detectors, this system integrates:

📡 Instant Remote Reporting
⚡ Automatic Machine Shutdown
🏭 Industrial RS485 Communication
🔒 Workplace Safety Enforcement
🔧 Expandable Industrial IoT Architecture

The same controller platform can be adapted for:

🌱 Smart Agriculture Monitoring
⚙️ Machine Health Monitoring
🌡️ Environmental Monitoring
💧 Water Management Systems
🏭 Industrial Automation Applications

---

## 🎯 Expected Impact

✅ Reduce workplace accidents
✅ Improve industrial safety compliance
✅ Prevent unsafe machine operation
✅ Enable real-time incident reporting
✅ Reduce dependency on manual supervision
✅ Support Industry 4.0 and Smart Factory initiatives

---

## 🏭 Applications

🔹 Manufacturing Industries
🔹 CNC Machine Shops
🔹 Chemical Processing Plants
🔹 Construction Sites
🔹 Mining Industries
🔹 Warehouse Facilities
🔹 Industrial Automation Systems
🔹 Smart Factory Environments

---
🌳POWER TREE
<img width="1536" height="1024" alt="ChatGPT Image Jun 20, 2026, 12_27_44 PM (2)" src="https://github.com/user-attachments/assets/87ed474c-b69f-4dcb-a1ba-ff9fcb35f8bc" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

🎬3D MODEL


<img width="473" height="645" alt="3D Model" src="https://github.com/user-attachments/assets/d2aeacfc-11b4-4048-9089-b9c6e1cb2646" />



-----------------------------------------------------------------------------------------------------------------------------------------------------------------
📁SCHEMATIC

<img width="1206" height="810" alt="SCHEMATIC" src="https://github.com/user-attachments/assets/76ac40fa-28d9-41ad-b605-9fa4666e05fa" />


-----------------------------------------------------------------------------------------------------------------------------------------------------------------


🧩LAYOUT

🔴TOP LAYER  

<img width="462" height="632" alt="Top Layer" src="https://github.com/user-attachments/assets/f287a946-17d9-44ed-870b-6292129b59a1" />




🔵BOTTOM LAYER

<img width="643" height="682" alt="Bottom Layer" src="https://github.com/user-attachments/assets/9b144a51-7efe-46be-bd75-5a4213d67ded" />


-----------------------------------------------------------------------------------------------------------------------------------------------------------------

🗂️DRAFTSMAN 

<img width="1118" height="791" alt="Draftsman Doc" src="https://github.com/user-attachments/assets/95f066bc-fd59-485b-bf46-94f459de868b" />

-----------------------------------------------------------------------------------------------------------------------------------------------------------------


🧾BOM

<img width="986" height="647" alt="BOM" src="https://github.com/user-attachments/assets/fd39eb03-80e8-4a60-a7f9-68ef387ffaaa" />

------------------------------------------------------------------------------------------------------------------------------------------------------------------

📚LIBRARIES

<img width="790" height="557" alt="Libraries" src="https://github.com/user-attachments/assets/d23e3192-f2c9-4cc9-99f3-843dd6b07b35" />


------------------------------------------------------------------------------------------------------------------------------------------------------------------

📈DRC REPORT 

<img width="1581" height="802" alt="DRC Report" src="https://github.com/user-attachments/assets/862a9ba0-fd89-4a05-8c2c-ee98b7f80592" />

------------------------------------------------------------------------------------------------------------------------------------------------------------------

📄ERC REPORT

<img width="815" height="428" alt="ERC REPORT" src="https://github.com/user-attachments/assets/723b60ff-b0f0-4787-ba86-3c52dddaac01" />

------------------------------------------------------------------------------------------------------------------------------------------------------------------

⚙️WORKING

<img width="1536" height="1024" alt="ChatGPT Image Jun 20, 2026, 03_11_59 PM" src="https://github.com/user-attachments/assets/0f520263-48cd-422f-b794-a5f0bc591356" />

---------------------------------------------------------------------------------------------------------------------------------------------------------------

🎯 Output / Results 



The developed Industrial Safety Monitoring and Workplace Alcohol Detection System was successfully designed, simulated, and implemented using the PIC16F877A microcontroller.



### ✅ Functional Results



🔹 Successfully detected alcohol concentration using the MQ3 sensor.



🔹 Continuously monitored sensor values and processed them through the PIC16F877A ADC module.



🔹 Displayed real-time system status and safety information on the OLED display.



🔹 Activated the buzzer alarm when the detected alcohol level exceeded the predefined threshold.



🔹 Automatically disabled machine operation using the relay-based machine shutdown mechanism.



🔹 Successfully transmitted instant alert notifications through the GSM communication module.



🔹 Enabled industrial communication support through the RS485 interface for future SCADA and Industrial IoT integration.



🔹 Successfully programmed and debugged using the ICSP interface.



---



## 📊 PCB Design Results



✅ Custom PCB successfully designed in Altium Designer.



✅ Design Rule Check (DRC) completed with:



```text

Warnings          : 0

Rule Violations   : 0

Unrouted Nets     : 0

```



✅ Compact PCB dimensions:



```text

74.42 mm × 115.89 mm

```



✅ PCB layout optimized for:



* Signal Integrity

* EMI Reduction

* Industrial Reliability

* Modular Expansion



------------------------------------------------------------------------------------------------------------------------------


### 🚀 Tagline

**"A Smart Industrial IoT Safety Controller that Detects Alcohol Impairment, Prevents Unsafe Machine Operation, and Instantly Reports Critical Events for Enhanced Workplace Safety."**
