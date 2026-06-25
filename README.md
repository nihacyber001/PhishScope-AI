# PhishScope AI

Advanced Cybersecurity Email Analysis Platform designed to dynamically detect phishing attempts.

## Features
- **Heuristic Content Analyzer:** Scans email text for malicious patterns, urgency, and credential requests.
- **Link Analysis:** Extracts URLs and queries the VirusTotal v3 API for vendor verdicts.
- **Risk Engine:** Automatically calculates an overall severity score (Clean, Suspicious, High, Critical).
- **Premium UI:** Features a modern glassmorphism design with asynchronous analysis for a smooth UX.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR-USERNAME/phishing-detection.git
cd phishing-detection
```

2. Create a virtual environment and install dependencies:
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

3. Configure your API Keys:
Create a `.env` file in the root directory and add your VirusTotal API key:
```
VT_API_KEY=your_virustotal_api_key_here
```

4. Run the application:
```bash
python app.py
```

5. Open your browser to `http://127.0.0.1:5000`
