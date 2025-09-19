# Warehouse Dashboard (Streamlit)

Professional demo dashboard for **Agriculture & Forestry**.

## Features
- Owner login via `?admin=OWNER_KEY`
- Temporary client tokens (editor/viewer) with expiry
- Clients can update data temporarily (reset on logout)
- Warehouse KPIs (Open, Processing, Shipped, Invoiced)
- Interactive filters
- Excel/PDF export
- English-only interface
- Professional UI with hidden deploy menu

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Streamlit Cloud Secrets
```
OWNER_KEY = "admin12345"
BASE_URL = "https://<app-name>.streamlit.app/"
CLIENT_COMPANY = "Agriculture & Forestry"
```
