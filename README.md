# Real-time-data-processsing
python ETL framework for Real time data pprocessing
# 🚗 Urban Parking Dynamic Pricing Project

This project implements a real-time dynamic pricing system for urban parking lots using Python, pandas, NumPy, and Bokeh. It's part of the **Summer Analytics 2025 Capstone Project** hosted by the Consulting & Analytics Club × Pathway.

---

## 📈 Project Overview

Parking prices are updated dynamically based on:
- Historical occupancy patterns
- Real-time queue lengths
- Nearby traffic congestion
- Special event indicators
- Vehicle type (car, bike, bus, truck)
- Nearby competitor pricing (geolocation-based)

---

## 🧠 Models Implemented

### ✅ Model 1: Linear Pricing
Price increases linearly with occupancy rate.

### ✅ Model 2: Demand-Based Pricing
Price responds to a calculated demand function using queue, traffic, day type, and vehicle weight.

### ✅ Model 3: Competitive Pricing
Price adjusts based on nearby parking lots using latitude/longitude distance and competitor prices.

---

## 🛠 Technologies Used

- **Python** (pandas, numpy)
- **Bokeh** (interactive dashboards)
- **Geopy** (distance between parking lots)
- **Pathway-style Simulation** (latency, row tracking, stream emulation)

---

## 📊 Interactive Dashboard

![Dashboard Preview](dashboard_preview.png)
) <!-- Optional: Add your screenshot if uploaded -->

The Bokeh dashboard shows:
- Real-time pricing trends for each model
- System metrics (messages processed, latency, row count)

---

## ▶️ Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<25pravin/<Real-time-data-processing>/blob/main/<Real Time Data Processing
>.ipynb)

> Replace `<your-username>`, `<repo-name>`, and `<your-notebook-name>` above with your actual GitHub info.

---

## 📂 Files Included

- `urban_parking_pricing.ipynb` – Colab notebook with full implementation
- `dataset.csv` – Simulated input data
- `README.md` – Project documentation (this fil)

👤 GitHub: [@25pravin](https://github.com/25pravin)
