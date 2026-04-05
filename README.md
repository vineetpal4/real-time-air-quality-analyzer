# 🌍 Real-Time Air Quality Analyzer

> Monitor, analyze & visualize live AQI data using Python, Streamlit & OpenAQ API

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-red?style=flat-square&logo=streamlit)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

## 🎯 About
A real-time dashboard to monitor air quality across cities using live API data.
Tracks PM2.5, PM10, CO₂, O₃, NO₂ and calculates AQI with trend charts and health recommendations.

## ✨ Features
- 📡 Live AQI data from OpenAQ & IQAir APIs (refreshes every 60s)
- 🗺️ Interactive map showing pollution hotspots
- 📈 24h / 7-day historical trend charts (Plotly)
- 🚨 Threshold-based alerts via email/SMS
- 🤖 AI-powered health tips based on AQI level
- 📄 One-click PDF report download

## 🛠️ Tech Stack
Python · Streamlit · Pandas · Plotly · Folium · OpenAQ API · Scikit-learn

## 🚀 Setup

```bash
git clone https://github.com/YOUR_USERNAME/real-time-air-quality-analyzer
cd real-time-air-quality-analyzer
pip install -r requirements.txt
cp .env.example .env   # add your API key
streamlit run app.py
```

## 📁 Project Structure
```
├── app.py               # Streamlit entry point
├── modules/
│   ├── fetcher.py       # API data fetcher
│   ├── analyzer.py      # AQI calculations
│   ├── visualizer.py    # Charts & maps
│   └── alerts.py        # Alert system
├── data/                # Cached data
├── requirements.txt
└── .env.example
```

## 📸 Demo
![Dashboard Preview](assets/demo.png)

## 🙋 Author
Made with ❤️ by [Your Name](https://github.com/YOUR_USERNAME)

## 📜 License
MIT — free to use and modify.
