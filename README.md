**SQLSniper** is a robust Python tool designed to detect time-based blind SQL injections in HTTP request headers. It enhances the security assessment process by rapidly scanning and identifying potential vulnerabilities using advanced multi-threaded techniques.

##Key Features
- **Time-Based Blind SQL Injection Detection:** Pinpoints potential SQL injection vulnerabilities in HTTP headers.
- **Multi-Threaded Scanning:** Offers faster scanning capabilities through concurrent processing.
- **Discord Notifications:** Sends alerts via Discord webhook for detected vulnerabilities.
- **False Positive Checks:** Implements response time analysis to differentiate between true positives and false alarms.
- **Custom Payload and Headers Support:** Allows users to define custom payloads and headers for targeted scanning.


## Installation
```
git clone https://github.com/danialhalo/SQLSniper.git
cd SQLSniper
chmod +x SQLSniper.py
pip3 install -r requirements.txt
```
