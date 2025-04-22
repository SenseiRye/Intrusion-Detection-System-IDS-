# Intrusion-Detection-System-IDS-
ThIs IDS monitors network traffic, identifies suspicious activity such as port scans or SYN flood attacks, and provides real-time alerts. Ideal for learning and small-scale environments.

Features
	•	Real-time network packet capture and analysis
	•	Detection for:
	•	Port scanning
	•	SYN flood attacks
	•	Suspicious ICMP traffic (e.g. ping sweeps)
	•	Event logging and optional email alerting
	•	Easy-to-extend detection rules

Prerequisites
	•	Python 3.8+
	•	Scapy (`pip install scapy`)
	•	(Optional) Email account for sending alerts (SMTP settings)
	•	Admin/root access for capturing packets
