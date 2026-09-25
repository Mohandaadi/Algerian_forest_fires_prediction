# Forest Fire Weather Index Prediction

A Flask web application that predicts the Forest Fire Weather Index (FWI) using a trained Ridge Regression model.

## Setup

Create and activate a virtual environment, then install the dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

## Run

```powershell
python application.py
```

Open http://127.0.0.1:5000 in a browser.

The trained model and scaler are stored in `models/`. The notebooks and source datasets are stored in `notebooks/`.