# Law & AI Academic Research

A Streamlit-based research tool for legal scholarship, AI liability, causation, and explainable AI.

## Deployment status
This repository currently contains **deployment scaffolding only**. The complete V2.2 Python application has not yet been uploaded. Streamlit deployment requires the missing `app/main.py` and Python packages under `clients/`, `core/`, `models/`, `repositories/`, and `services/`.

## Local run after uploading V2.2 source
```powershell
py -m pip install -r requirements.txt
python -m streamlit run app/main.py
```

## Streamlit Community Cloud
- Repository: `lamquochuy-st/law-ai-academic-research`
- Branch: `main`
- Main file path: `app/main.py`
- Set API keys/email in **Advanced settings → Secrets**, not in GitHub files.
- The SQLite database and downloaded PDF files are ephemeral on Streamlit Community Cloud; use persistent external storage for production.

## Security
Do **not** commit `.env`, `.streamlit/secrets.toml`, `data/`, databases, PDF files, or API keys.
