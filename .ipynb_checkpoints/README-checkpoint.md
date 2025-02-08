# PlantSmart
# AgriSense: Smart Soil Analyzer

## Project Overview
*AgriSense* is an *IoT-based soil monitoring system* that measures essential soil contents like *Sulfur, Nitrogen, Oxygen, Moisture, pH, and Temperature*. The device provides **real-time data analysis** to help farmers optimize soil health and crop yield.

---

## Team Members

| Name              | Roll Number  |
|------------------|-------------|
| *Aditya Kumar*   | 22051222     |
| *Affan Ahmed*    | 22051567     |
| *Atul Kumar*     | 22053933     |
| *Abhinandan Maji* | 2205784      |

---

## Project Structure

### 1️⃣ Hardware Development

#### Goal
Design and implement an *IoT-based soil monitoring device* to measure essential soil parameters.

#### Tasks
✅ *Sensor Selection & Integration*
- Choose sensors for *Nitrogen, Sulfur, Oxygen, Moisture, pH, and Temperature*.
- Interface sensors with a *Microcontroller (ESP32, Arduino, or Raspberry Pi)*.
- Ensure proper *power supply and weatherproof casing*.

✅ *Circuit Design & Prototyping*
- Design the *PCB circuit* for sensor connections.
- Develop a *low-power consumption system* for long-term use.

✅ *Testing & Calibration*
- Test each sensor’s accuracy with real soil samples.
- Adjust readings for *environmental factors*.

#### Technologies & Components
- *Microcontroller*: ESP32 / Arduino / Raspberry Pi
- *Sensors*: Soil Moisture, pH, NPK (Nitrogen, Phosphorus, Potassium), Temperature
- *Software*: Arduino IDE, Python, C++
- *Tools*: Soldering Kit, Multimeter, PCB Design Software

---
### 2️⃣ IoT & Data Transmission
#### Goal
Send real-time soil data to a cloud server for analysis and remote monitoring.

#### Tasks
✅ *Microcontroller Programming*
- Read sensor values and preprocess the data.
- Implement *error handling* for sensor failures.

✅ *Cloud Integration*
- Send data to *Firebase, Thingspeak, AWS IoT, or MQTT broker*.
- Implement *Wi-Fi/Bluetooth* communication for real-time data transfer.

✅ *Dashboard Development*
- Display real-time data on a *web or mobile application*.
- Visualize soil content trends over time.

#### Technologies & Libraries
- *Languages*: Python, C++, JavaScript
- *IoT Protocols*: MQTT, HTTP, WebSockets
- *Cloud Services*: Firebase, AWS IoT, Thingspeak
- *Libraries*: Adafruit Sensor Library, ESPAsyncWebServer

---
### 3️⃣ Data Analysis & AI-Based Recommendations
#### Goal
Analyze soil data to provide *AI-driven recommendations* for better crop management.

#### Tasks
✅ *Data Preprocessing*
- Normalize and clean sensor data.
- Handle missing values and outliers.

✅ *Machine Learning for Soil Health Prediction*
- Train models to detect *deficient nutrients*.
- Recommend *fertilizers and watering schedules* based on soil data.

✅ *AI-Powered Alerts*
- Send *mobile notifications* if soil conditions are poor.
- Implement *automated irrigation triggers* if moisture is too low.

#### Technologies & Libraries
- *Languages*: Python
- *Libraries*: Scikit-learn, TensorFlow, Pandas, NumPy
- *ML Models*: Decision Trees, Random Forest, LSTMs

---
### 4️⃣ Web/Mobile Application Development

#### Goal
Create a user-friendly interface for farmers to *monitor soil health* and receive alerts.

#### Tasks
✅ *Front-End Development*
- Build a mobile app or web dashboard.
- Display *real-time soil data, trends, and AI-based suggestions*.

✅ *Back-End Development*
- Develop *REST APIs* to connect IoT data with the app.
- Store soil readings in a *database (MongoDB, Firebase, PostgreSQL)*.

✅ *Deployment*
- Host the web app on *AWS/GCP/Azure*.
- Implement *secure user authentication*.

#### Technologies & Libraries
- *Front-end*: React.js, Flutter, Kotlin
- *Back-end*: Flask, FastAPI, Django
- *Database*: Firebase, PostgreSQL, MongoDB
- *Cloud*: AWS, GCP, Azure

---
## Setup & Installation
1. *Clone the repository*
   ```sh
   git clone https://github.com/your-repo/AgriSense.git  
   cd AgriSense  
   ```
   
2. *Set up the IoT device*
   - Connect the sensors to *ESP32/Arduino*.
   - Upload the firmware using *Arduino IDE/Python*.

3. *Run the Cloud API Server*
   ```sh
   cd backend  
   pip install -r requirements.txt  
   python app.py  
   ```
   
4. *Start the Front-End Application*
   ```sh
   cd frontend  
   npm install  
   npm start  
   ```

---
## Future Enhancements

- *AI-Based Soil Deficiency Predictions*
- *Automated Irrigation Control*
- *Blockchain for Secure Data Storage*

---
## Conclusion

*AgriSense* is a smart IoT system designed to *help farmers monitor soil health in real time*. By leveraging IoT, AI, and cloud computing, it aims to **improve agricultural efficiency** and *reduce manual soil testing efforts*.
