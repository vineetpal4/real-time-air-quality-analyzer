 Real-Time Air Quality Analyzer
Monitor, analyze & visualize live AQI data using Python, Streamlit & OpenAQ API

Python Streamlit License Status

About
A real-time dashboard to monitor air quality across cities using live API data. Tracks PM2.5, PM10, CO₂, O₃, NO₂ and calculates AQI with trend charts and health recommendations.

Features
Live AQI data from OpenAQ & IQAir APIs (refreshes every 60s)
Interactive map showing pollution hotspots
24h / 7-day historical trend charts (Plotly)
Threshold-based alerts via email/SMS
AI-powered health tips based on AQI level
One-click PDF report download
Tech Stack
Python · Pandas · numpy · seaborn · OpenAQ API · matplotlib

Project Structure
├── app.py               # Streamlit entry point
├── modules/
│   ├── fetcher.py       # API data fetcher
│   ├── analyzer.py      # AQI calculations
│   ├── visualizer.py    # Charts & maps
│   └── alerts.py        # Alert system
├── data/                # Cached data
├── requirements.txt
└── .env.example
Demo
Dashboard Preview

Author
Made by Yukti Verma

License
MIT — free to use and modify.
