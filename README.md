# ⚡ TransVolt Voltage Dashboard

A lightweight Flask web application for visualizing and analyzing voltage data.  
It generates *interactive dashboards* with multiple charts and data tables, including:

- 📈 *Original Voltage Data*
- 🔴 *5-Day Moving Average*
- 🟢 *Local Peaks & Troughs*
- ⚠ *Voltage Below 20 Detection*
- ⬇ *Downward Acceleration Points*

All charts are rendered server-side using *Matplotlib* and served in a clean Bootstrap-based interface.

---

## 🚀 Features

- *Multiple Data Visualizations*
  - Moving averages
  - Local peak & trough detection
  - Voltage drop events (< 20)
  - Downward slope acceleration points
- *Automatic Data Analysis*
  - Uses scipy.signal.find_peaks for event detection
  - Detects and logs acceleration points into CSV
- *Single Webpage Dashboard*
  - All plots and tables are shown together
- *Lightweight Hosting*
  - No Streamlit or dashboard-specific services

---
