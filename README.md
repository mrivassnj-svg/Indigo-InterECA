# InterECA — Interactive Error Code Analyzer

InterECA is a no-nonsense, web-based tool designed to quickly identify and explain POSIX, HTTP, and Misc/BIOS/Document error codes. It presents clear, actionable insights in a structured, professional format.

## Features
- Category-based error analysis (POSIX, HTTP, Misc/BIOS/Document)
- Interactive dropdown selection
- Clean, readable HTML table output
- Severity highlighting for rapid risk assessment
- Designed for Google Colab and local execution

## Use Cases
- System administrators troubleshooting POSIX errors
- Web developers diagnosing HTTP status codes
- Security analysts and engineers reviewing firmware or document-related errors
- Educational demonstrations of error classification and remediation

## Running in Google Colab
1. Upload the repository or required files to Colab
2. Ensure CSV files are placed in `/content/`
3. Run `app.py` or the provided notebook
4. Interact with the Gradio UI directly in Colab

## Local Installation
```bash
git clone https://github.com/yourusername/InterECA.git
cd InterECA
pip install -r requirements.txt
python src/app.py
