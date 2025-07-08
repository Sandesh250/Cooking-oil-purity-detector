# Cooking Oil Purity Detection for Public Use

A smart IoT-based system to monitor the quality of cooking oil in real-time using pH, RGB color, and turbidity sensors.

## 🔍 Problem
Reused cooking oil in public food stalls poses health risks like heart disease and cancer. Existing methods rely on visual inspection, which is unreliable.

## 🚀 Solution
We developed a low-cost sensor system that:
- Uses *pH, **RGB color, and **turbidity* sensors
- Connects via *ESP8266 Wi-Fi* to *ThingSpeak*
- Classifies oil into: ✅ Pure, ⚠ Moderately Used, ❌ Waste
- Shows live status on *LCD display*
- Uploads data to the cloud for *remote monitoring*

## 🧰 Tech Stack
- Arduino Uno
- TCS34725 RGB Sensor
- pH Sensor Module
- Turbidity Sensor
- ESP8266 Wi-Fi Module
- LCD (16x2)
- ThingSpeak IoT Cloud

## 📊 Sample Output
- Drop in pH = higher acidity
- Faded RGB = oil degradation
- Turbidity increase = particles in reused oil

## 📷 Screenshots

![ThingSpeak Dashboard](ThingSpeak_Screenshots/dashboard.png)

## 🎥 Demo
📺 [Demo Video Link](https://drive.google.com/file/d/1G8bF1nyLyU7gbWfczf-bUpR0DWkEOmlV/view?usp=drive_link)

## 👨‍💻 Team
- Ramakrishna M N  
- Prajwal A U  
- Sandesh S P  
- Lohith P  
- Lalan P  
- 👩‍🏫 Guided by: Dr. Varuna M  

## 🔗 References
1. [Economic Times Article](https://health.economictimes.indiatimes.com/news/industry/sixty-pc-of-used-cooking-oil-finds-its-way-back-into-food-stream-says-study/93818373)
2. [PubMed Study](https://pubmed.ncbi.nlm.nih.gov/37877148/)

## 📜 License
MIT License
