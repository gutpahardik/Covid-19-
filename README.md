 COVID-19 Pandemic Dashboard

Interactive **COVID-19 Pandemic Dashboard** built using **Dash**, **Plotly**, and **Pandas**. Visualizes state-wise COVID-19 data, commodity usage, and zone distribution.

---

## Technologies Used
- Python 3
- Dash
- Plotly
- Pandas
- Bootstrap 5

---

## Features
1. **Key Metrics Cards**
   - Total cases
   - Active cases
   - Recovered cases
   - Total deaths

2. **Bar Chart by State**
   - Filterable by status: All, Hospitalized, Recovered, Deceased

3. **Commodity Usage Line Chart**
   - Filterable by commodity: All, Mask, Sanitizer, Oxygen

4. **Pie Chart for Zones**
   - Distribution by zone: Red, Green, Blue, Orange

5. **Responsive Layout**
   - Bootstrap 5 based

---

## Dataset
- `state_wise_daily data file IHHPET.csv`
- Columns include: `State`, `Status`, `Total`, `Hospitalized`, `Recovered`, `Deceased`, `Mask`, `Sanitizer`, `Oxygen`, `Zone`

---

## Installation
1. Clone the repository:
```bash
git clone <repository_url>
cd <repository_folder>
Install dependencies:

bash
Copy code
pip install dash plotly pandas
Place the dataset in the project folder.

Run the app:

bash
Copy code
python app.py
Open in browser:

cpp
Copy code
http://127.0.0.1:8050/
How It Works
Reads data using Pandas.

Calculates key metrics dynamically.

Creates interactive charts using Plotly.

Uses Dash callbacks for dropdown-based interactivity.

Future Enhancements
Add time-series analysis of COVID-19 cases.

Integrate real-time API for live data.

Include predictive analytics for future case trends.

Enhance visualizations with hover info and color-coded zones.

pgsql
Copy code
