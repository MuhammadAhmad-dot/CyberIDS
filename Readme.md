# Eagle Eye
This project is an intrusion detection system that analyzes network traffic for anomalies using a combination of static rules and artificial intelligence. The system uses a network analyzer written in C++ to capture traffic and then processes it through a set of predefined rules. Any anomalies are then passed on to the AI component for further inspection.

# Features
#### Static rule-based analysis
#### AI-based analysis
#### Network analyzer written in C++
#### Detection of network anomalies

# Acknowledgments
Thanks to [**TRYHACKME**](https://tryhackme.com/) for providing the inspiration for this project.


# How to Run
1. g++ packet.cpp -o a.out
2. sudo ./a.out interface ( interface either wlan0 or docker0 in case of dvwa)
3. Put payload in dvwa or on this site http://testhtml5.vulnweb.com/ from files and it will detect the payloads.