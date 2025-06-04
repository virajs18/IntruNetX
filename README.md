IntruNetX-Realtime-Network-Intrusion-Detection-System
"Monitoring the unseen, securing the unknown."

IntruNet IDS is a lightweight real-time Intrusion Detection System (IDS) built using Flask, Scapy, and Machine Learning.
It captures live network packets, analyzes traffic flows, predicts potential intrusions, and allows the user to block/unblock suspicious IP addresses — all through a clean web dashboard.

Features 🚀
Real-time network traffic capture
Flow-based packet feature extraction
Machine Learning prediction (attack detection)
Block and Unblock IPs dynamically
CSV Export for captured traffic
Responsive web dashboard with Bootstrap
Lightweight and easy to run locally
Technologies Used 🛠️
Python 3.10+
Flask (Backend Web Server)
Scapy (Packet Sniffing)
scikit-learn (ML Model for prediction)
Bootstrap 5 (Frontend styling)
HTML + JS (Frontend dashboard)
Installation 📦
Clone the Repository

git clone https://github.com/Rushi19-04/IntruNetX-Realtime-Network-Intrusion-Detection-System.git
cd IntruNet-IDS
Install the required libraries

pip install -r requirements.txt
Check/Install WinPcap/Npcap (For packet sniffing on Windows)

Place the Trained ML Model

Ensure model.pkl and scaler.pkl are inside the model/ directory.
How to Run 🚀
Start the Flask server:

python app.py
Open your browser and visit:

http://127.0.0.1:5000
Use the Web UI to:

Start Capture
Stop Capture
Monitor Live Traffic
Block/Unblock IPs
Export Captured Data to CSV
Project Structure 📂
IntruNet-IDS/
│
├── app.py                 # Main Flask Application
├── predict.py             # Machine Learning Predictor
├── model/
│   ├── model.pkl          # Pre-trained ML Model
│   └── scaler.pkl         # Feature Scaler
├── templates/
│   └── home.html          # Frontend Web Dashboard
├── static/                # (optional for css/js if extended)
├── captured_traffic.csv   # Exported CSV (after clicking export)
├── requirements.txt       # Python dependencies
└── README.md              # Project Documentation
Requirements 🧪
Python 3.10 or higher
Flask
Scapy
scikit-learn
pandas
joblib
numpy
(Already listed inside requirements.txt)

Future Improvements 🌟
Add automatic alerting/email notification on attacks
Add graphs and visualizations (e.g., live traffic graphs)
Support for offline PCAP file analysis
Extended prediction with multiple attack categories
Integrate deeper packet inspection
Disclaimer ⚡
IntruNet IDS is meant for educational, research, and local network monitoring purposes only. Unauthorized scanning or interception of third-party networks without consent is illegal.

Credits 🙌
Made with ❤️ by Rushikesh | Viraj | Devendra | ShubhamIntruNetX
