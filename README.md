https://github.com/hposton/python-for-cybersecurity

# Python Cyber Security Projects

## Topics
- Socket Programming
- DNS Enumeration
- Port Scanning
- Packet Analysis
- Automation

## Tools Used
- Python
- Scapy
- Socket
- Wireshark
- 
## python-cybersec/
│
├── basics/
├── networking/
├── automation/
├── scanners/
├── cryptography/
├── packet-analysis/
├── notes/
├── README.md
└── requirements.txt

# python roadmap

## 1. Variables and Data Types

```python
name = "Prachi"
port = 80
is_open = True
```

Learn:

* strings
* integers
* floats
* booleans

---

## 2. Input and Output

```python
target = input("Enter IP: ")
print(target)
```

You'll use this in every tool.

---

## 3. Conditions

```python
if port == 80:
    print("HTTP")
```

Learn:

* if
* elif
* else

---

## 4. Loops ⭐ Very Important

```python
for port in range(1, 100):
    print(port)
```

You'll use loops in:

* port scanners
* log analysis
* automation

---

## 5. Functions ⭐ Very Important

```python
def scan_port(port):
    print(port)

scan_port(80)
```

Makes code reusable.

---

## 6. Lists

```python
ports = [22, 80, 443]

for port in ports:
    print(port)
```

Used everywhere.

---

## 7. Dictionaries

```python
services = {
    80: "HTTP",
    443: "HTTPS"
}

print(services[80])
```

Very useful for networking tools.

---

## 8. Exception Handling ⭐

```python
try:
    print(services[22])
except:
    print("Not found")
```

Prevents programs from crashing.

---

## 9. File Handling

```python
with open("results.txt", "w") as file:
    file.write("Port 80 Open")
```

Used for:

* logs
* scan reports
* automation

---

## 10. Modules and Imports

```python
import socket
import os
```

Essential for cyber tools.

---

## 11. Learn These Libraries

### socket

```python
import socket
```

For:

* port scanners
* banner grabbing
* networking

### requests

```python
import requests
```

For:

* APIs
* web automation

### os

```python
import os
```

For:

* files
* directories

### subprocess

```python
import subprocess
```

For running Linux commands.

### hashlib

```python
import hashlib
```

For hashes:

* MD5
* SHA256


## Python Roadmap

1. Variables
2. Input/Output
3. If/Else
4. Loops
5. Functions
6. Lists
7. Dictionaries
8. Try/Except
9. File Handling
10. Imports
11. `socket`
12. `requests`



/?utm_source=chatgpt.com)
