# Python Intrusion Detection System (IDS) 🛡️

A lightweight **network intrusion detection system** built with Python and Scapy. Detects SYN floods, port scans, and suspicious traffic patterns in real-time.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scapy](https://img.shields.io/badge/Scapy-2.4.5-red)

## Features
- 📦 **Packet capture** with multithreading
- 🔍 **Hybrid detection** (signature + anomaly-based)
- ⚡ Real-time **threat alerts** with confidence scoring
- 🧪 **Mock data testing** (no live network needed)

## Quick Start
```bash
git clone https://github.com/yourusername/python-ids.git
cd python-ids
pip install scapy scikit-learn

# Run tests
python ids_test.py

# Start live monitoring (requires sudo)
sudo python ids.py


graph TD
    A[Packet Capture] --> B[Traffic Analyzer]
    B --> C[Detection Engine]
    C --> D[Alert System]
