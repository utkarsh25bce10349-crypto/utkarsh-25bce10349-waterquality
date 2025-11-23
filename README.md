# utkarsh-25bce10349-waterquality
Water Quality Dashboard
This dashboard visualizes water quality data, including time series trends from tabular data and spatial representations from raster data.

Project Structure
water_quality_dashboard/
├── app.py              # Main Dash application script
├── requirements.txt    # Python dependencies
├── utils/              # Utility scripts (e.g., data loading)
│   └── data_loader.py
├── data/               # Data files (Excel, potentially raster)
│   ├── IndicesData_Lakes.xlsx
│   └── Fake_IndicesData_Lakes.xlsx
├── raster_output/      # (Optional) Directory for saved generated images
└── README.md           # This file
Setup and Installation
Clone the repository (if applicable):

git clone <repository-url>
cd water_quality_dashboard
Create a virtual environment (recommended):

python -m venv venv
Activate the environment

pip install -r requirements.txt
Running the Application Locally
Ensure your virtual environment is activated.
Navigate to the water_quality_dashboard directory in your terminal.
Run the Dash application:
python pp.py
Open your web browser and go to: http://127.0.0.1:8050/
The application should now be running locally. The File Monitor tab shows which data files have been loaded. If you add new compatible files to the data/ directory while the app is running, they should be detected automatically (refresh might take a few seconds).