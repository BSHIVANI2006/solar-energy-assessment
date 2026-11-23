# Smart Solar Energy Assessment System

## Project overview
A browser-based educational prototype that estimates rooftop solar capacity, electricity generation, potential bill savings and indicative CO2 emissions avoided.

## Files
- `index.html` — complete application (HTML, CSS and JavaScript are included in this file).

## How to run in VS Code
1. Extract the ZIP file.
2. Open the `Smart_Solar_Energy_Assessment` folder in VS Code.
3. Open `index.html`.
4. Run it using the VS Code Live Server extension, or double-click `index.html` to open it in a browser.
5. Enter the building details and click **Assess Solar Potential**.

## Input data and possible sources
- Location: user input.
- Usable rooftop area: user measurement or building plan.
- Peak sunlight hours: local solar resource data, such as NASA POWER.
- Electricity tariff and monthly bill: user's electricity bill / local electricity provider.
- Grid emission factor: a published electricity-grid emissions factor appropriate to the location and year.

## Model assumptions
- 100 sq. ft. usable roof area per 1 kW (simplified prototype assumption).
- Performance ratio: 0.75.
- Monthly generation = capacity (kW) × peak sunlight hours/day × 30 × 0.75.
- Estimated savings are capped at the entered monthly bill.
- CO2 avoided = annual estimated generation × user-entered grid emission factor.

These are screening estimates only. Actual results depend on roof orientation, shading, panel technology, temperature, inverter losses, maintenance, tariffs, net-metering and local regulations. The tool is not a professional engineering survey or a guaranteed financial estimate.

## Technologies
HTML, CSS, JavaScript, browser-based calculations and data analytics (basic descriptive calculations). No AI or machine learning is claimed.
