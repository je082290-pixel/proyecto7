# proyecto7
proyecto7 para mi bootcam.
services:
  - type: web
    name: vehicles proyecto-7-streamlit
    env: python
    region: oregon 
    plan: free
    buildCommand: "pip install -r requirements.txt"
    startCommand: "streamlit run app.py" 
