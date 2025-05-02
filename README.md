# Linkt Cost Centre Bot

This project processes Linkt phone invoices and allocates mobile costs to predefined cost centres, handling unmatched entries by distributing them equally.

## Features
- PDF parsing using `pdfplumber`
- Cost centre mapping from phone numbers
- CLI and Streamlit interface
- Handles $0 cost entries and rounding

## 🔧 Requirements

Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 CLI Usage
```bash
python linkt_cost_centre_bot.py path/to/invoice.pdf
```

## 🌐 Streamlit Web App
```bash
streamlit run streamlit_app.py
```

## 📝 Notes
- Edit `cost_centre_map` in both files to suit your organisation.
- The Streamlit version includes a CSV download button.
