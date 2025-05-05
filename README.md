# 🌾 Agriculture Air Monitoring System

A simple Python-based system to simulate and monitor air quality in agricultural environments such as greenhouses or open fields. This project helps detect harmful atmospheric conditions using simulated sensor data and provides alerts and visualization.

---

## 🚀 Features

- Simulates real-time data for:
  - Temperature (°C)
  - Humidity (%)
  - CO₂ levels (ppm)
  - PM2.5 concentration (µg/m³)
- Alerts if values go beyond safe thresholds
- Optional graph plotting using `matplotlib`
- Easily extendable to use with real sensors (e.g., DHT22, MQ135)

---

## 🛠️ How It Works

1. The script simulates sensor data at 2-second intervals.
2. It logs the data and checks against predefined safe limits.
3. If `matplotlib` is installed, it generates a simple chart after monitoring ends.

---

## 🐍 Requirements

- Python 3.x
- Optional: `matplotlib` for data visualization

```bash
pip install matplotlib
output:
2025-05-05 12:30:01 - Air Data: {'temperature': 32.4, 'humidity': 66.1, 'co2': 790.0, 'pm25': 35.1}
2025-05-05 12:30:01 - WARNING - CO2 out of range: 790.0




Future Improvements
Real sensor integration

Cloud-based data logging (Firebase, InfluxDB)

Web dashboard or mobile app

Auto-control of fans or irrigation based on air quality





---
MIT LICENSE
You can save this as `README.md` and upload it directly to your GitHub repo root.

Would you like a `LICENSE` file or a basic `main.py` template to go along with it?
