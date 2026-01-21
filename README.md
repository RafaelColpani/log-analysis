# Objective

Analyze Windows Event Log (.log) files to practice and deepen knowledge in cybersecurity and data analysis.

# Challenge

- Identify all login attempts.
  - Detect failed logins and determine which accounts were affected.
  - Evaluate whether these failures indicate potential unauthorized access or malicious activity.

## Screenshots
<img src="/image/FinalOut.png" alt="Alt" width="400"/>

### Installation

1. Clone the project
2. Creating the Virtual Environment
```
python -m venv .venv
```
3. Turn on the environment
```
source .venv/bin/activate
```
4. Install the Python dependencies
```
pip install -r requirements.txt
```

### Log Source
This project uses publicly available Windows event samples: [Windows Event Samples](https://github.com/d4rk-d4nph3/Windows-Event-Samples).

---
> [!IMPORTANT]
> This is a study project aimed at learning in the area of ​​cybersecurity and data analysis.

> [!NOTE]
> This project uses sample event logs sourced from the public repository "Windows-Event-Samples". All IP addresses and hostnames are internal and not linked to real infrastructure.
