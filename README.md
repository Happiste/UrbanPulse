# UrbanPulse - Paris Traffic Dashboard
## Project Overview
UrbanPulse is an advanced traffic analysis project designed to provide insights into the traffic patterns in Paris. Using a combination of Python data analysis and Tableau visualizations, this project consolidates interactive and static insights for urban planning.


## Objectives
- Analyze Traffic Data: Understand hourly and daily traffic variations across Paris streets.
- Identify Congestion Trends: Visualize traffic states (e.g., fluid, saturated, blocked) to locate hotspots.
- Support Policy Decisions: Provide tools for policymakers and urban planners.


## Repository Structure
UrbanPulse/
├── cache/                         # Temporary processing files (optional)
├── dataset/
│   ├── comptages-routiers-permanents.csv  # Main traffic data
│   ├── referentiel-comptages-routiers.csv # Reference data
│   └── urbanpulse.csv                     # Cleaned and processed data
├── UrbanPulse.ipynb               # Jupyter Notebook with data processing steps
├── UrbanPulse.twb                 # Tableau Workbook for the interactive dashboard
├── urbanpulse_updated_heatmap.html # Python-generated heatmap for traffic
├── venv/                          # Python virtual environment
└── README.md                      # Project documentation


## How to Access the Dashboard
Access the Tableau dashboard here:[ UrbanPulse Dashboard](https://public.tableau.com/app/profile/jonathan.bitane/viz/UrbanPulse/UrbanPulseDashboard?publish=yes)

## How to Run Locally
### Prerequisites
1. Python 3.x must be installed.
2. Install the required Python libraries:

pip install pandas numpy matplotlib seaborn

3. Install Tableau Desktop or use Tableau Public.

### Steps
1. Clone the repository:

git clone https://github.com/your-username/UrbanPulse.git
cd UrbanPulse

2. Run the Jupyter Notebook for data processing:
jupyter notebook UrbanPulse.ipynb

This will clean, process, and generate visualizations.

Open UrbanPulse.twb in Tableau to explore the interactive dashboard or follow the link. 
NB: Due to the enormus amount of data, prefere using Tableau Desktop than Tableau Public 

## Dataset Description
The dataset contains hourly traffic flow measurements from various sensors across Paris. It includes:

Hourly Flow: Vehicle count per hour.
Day of Week: Day corresponding to the measurement.
Traffic State: Qualitative description of traffic flow (Fluid, Blocked, Saturated).


## Key Visualizations
Interactive Map: Shows the distribution of traffic in Paris.
Heatmap: Displays hourly traffic patterns for each day of the week.
Temporal Trends: Time-series of traffic flow across days.
Pie Chart: Proportion of traffic states.
Bar Chart: Hourly flow rates segmented by traffic state.

## Contact
Author: Jonathan Bitane
Email: jonathan.bitane@example.com


Feel free to contribute or share feedback to improve the project!

