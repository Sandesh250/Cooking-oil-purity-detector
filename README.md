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

## 📁 Repository Structure
