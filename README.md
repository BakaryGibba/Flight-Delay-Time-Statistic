# Flight Delay Analysis Dashboard

This project is a Dash application for visualizing various types of flight delays from 2010 to 2020. The dashboard provides insights into monthly delay trends by carrier, weather, national air system, security, and late aircraft categories, segmented by reporting airline.

## Project Overview

This Dash application presents a dashboard with the following key components:

1. **Application Title**
2. **Year Selection Input** - Allows users to select a year between 2010 and 2020.
3. **Delay Analysis Charts** - Visual representations of monthly delay averages segmented as follows:
   - **Segment 1:** Carrier and Weather Delays
   - **Segment 2:** National Air System and Security Delays
   - **Segment 3:** Late Aircraft Delay

## Libraries

The application requires the following Python libraries:
- `packaging`
- `pandas`
- `dash`
- `plotly`
- `httpx==0.20`

Install all dependencies with:
```bash
python3.11 -m pip install packaging pandas dash
pip3 install httpx==0.20 plotly
