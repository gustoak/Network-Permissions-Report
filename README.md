# Network Folder Permissions Collector

This Python project collects folder permissions from both network drives and local storage units. It generates a CSV report with detailed information about user permissions for each folder.

## Installation

Clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/network-folder-permissions.git
cd network-folder-permissions
pip install -r requirements.txt
```

Usage:

To run the script and collect folder permissions:
```bash
python src/permissions_collector.py
```
The report will be saved in the data folder as permissions_report.csv.

Testing
To run the tests:
```bash
pytest
```

**Project Structure**
```bash
The project is structured as follows:
network-folder-permissions/
│
├── src/
│   ├── __init__.py
│   ├── permissions_collector.py
│   ├── report_generator.py
│
├── tests/
│   ├── __init__.py
│   ├── test_permissions_collector.py
│   ├── test_report_generator.py
│
├── data/
│   ├── sample_report.csv
│
├── .gitignore
├── README.md
├── requirements.txt
└── setup.py
```
