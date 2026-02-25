# 🌍 CarbonAudit | Precision Emissions Tracker

**CarbonAudit** is a high-fidelity web application designed to track and analyze vehicular carbon footprints. Built during a 24-hour hackathon, this tool aligns logistics operations with the **EPA 2026** dataset and the **Paris Agreement 1.5°C pathway**.

## 🚀 Live Demo
[Insert your GitHub Pages link here once you enable it!]

## 🛠 Features
* **Multi-Vehicle Support:** Calculate footprints for Passenger Cars, Vans, Motorcycles, Heavy Trucks, and even Auto Rickshaws.
* **Fuel Logic:** Specialized tracking for Petrol, Diesel, CNG, and Electric (EV) power sources.
* **Bharat Stage (BS) Integration:** Incorporates emission multipliers based on Indian manufacturing standards (BS2, BS3, BS4, and BS6).
* **Environmental Context:** Translates "kg of CO₂" into relatable data, such as equivalent trees needed for offsetting or phone charging hours.
* **Visual Analytics:** Real-time Chart.js integration to compare personal footprints against science-based "Safe Limits."

## 📊 How it Works
The application uses a baseline emission factor ($EF$) multiplied by the distance traveled ($D$) and a vehicle-specific regulatory multiplier ($M$):

$$Total\ Emissions = D \times (EF_{baseline} \times M_{BS})$$

### Emission Multipliers used:
| Standard | Era | Multiplier |
| :--- | :--- | :--- |
| **BS6** | 2020+ | 1.0 (Baseline) |
| **BS4** | 2017-2020 | 1.3 |
| **BS3** | 2010-2017 | 1.8 |
| **BS2** | Pre-2010 | 2.5 |

## 💻 Tech Stack
* **Frontend:** HTML5, CSS3 (Custom properties/animations)
* **Typography:** Syne & DM Sans (via Google Fonts)
* **Charts:** Chart.js
* **Icons:** Lucide-style SVG icons

## 📜 How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/carbon-audit.git](https://github.com/YOUR_USERNAME/carbon-audit.git)
