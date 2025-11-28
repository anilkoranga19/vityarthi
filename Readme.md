# CabFare — Taxi Fare Estimation & Analysis Tool

##  Overview
CabFare is a lightweight Python project designed to estimate taxi fares using configurable pricing rules.  
It allows users to calculate fares based on distance and duration, apply surge multipliers, generate sample datasets, and run simple data analyses.  
This project serves as a clean, testable example of business-logic modeling and basic data processing.

---

##  Features
-  **Fare Calculation Engine**  
  Computes cost using base fare, per-km, and per-minute rates.

-  **Surge Pricing Support**  
  Apply configurable surge multipliers.

-  **Data Generation & Analysis**  
  Create synthetic ride datasets and generate summary statistics.

-  **Unit Tests Included**  
  Ensures accuracy of fare calculations.

-  **Python API + CLI Interface**  
  Use it programmatically or from the command line.

---

##  Technologies / Tools Used
- **Python 3.8+**
- **Standard library modules** (math, argparse, etc.)
- *(Optional)* **pandas** for data analysis  
- **pytest** for unit testing
- **Virtual environment (venv)** recommended

---

##  Installation & Running the Project

### 1. Clone the project
```bash
git clone https://github.com/yourusername/cabfare.git
cd cabfare

### 2. Create a virtual environment
```bash
git clone https://github.com/yourusername/cabfare.git
cd cabfare

### 3. Install dependencies
```bash
pip install -r requirements.txt

### 4. Run the fare calculator (CLI)
```bash
python -m cabfare.cli --distance 12.5 --duration 22

## Project Structure
cabfare/
├─ cabfare/
│  ├─ fare.py
│  ├─ cli.py
│  ├─ data/
│  ├─ tests/
├─ README.md
├─ statement.md
└─ requirements.txt
