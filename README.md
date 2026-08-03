# 🏎️ GT3 Vehicle Telemetry Analysis

## 📌 Project Overview
This project extracts, cleans, and visualizes high-frequency vehicle telemetry data from a Porsche 992 GT3 R navigating the Monza circuit. The data was generated in Assetto Corsa Competizione (ACC) and natively parsed into a Python Data Science environment.

## 🛠️ Tools & Libraries Used
* **Python** (Data processing and pipeline architecture)
* **Pandas** (Data cleaning, handling 56-channel multidimensional arrays, isolating lap deltas)
* **Matplotlib** (Data visualization, subplots, and vehicle dynamics dashboards)

## 📊 Key Findings & Diagnostics
By building a custom visualization dashboard linking Speed, Throttle, and Brake traces across a shared time-axis, I was able to mathematically prove a hardware malfunction.

The data visualization successfully identified severe potentiometer noise (fluttering) on the throttle pedal during heavy braking zones, which was actively extending braking distances and destabilizing the car's aerodynamic platform.
