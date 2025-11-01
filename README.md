# DVSA OBS Automation

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

**Advanced DVSA browser automation with fingerprint spoofing & 75% cost reduction vs Multilogin.**

---

## 📖 Overview

`dvsa-obs-automation` is a sophisticated automation tool designed specifically for interacting with the DVSA (Driver and Vehicle Standards Agency) Obs (Officer Booking System). It leverages advanced fingerprint spoofing techniques to mimic genuine user behavior, significantly reducing the risk of detection while offering a 75% cost reduction compared to commercial alternatives like Multilogin.

## ✨ Features

- **Advanced Fingerprint Spoofing:** Masks automation fingerprints (canvas, WebGL, audio context, fonts, etc.) to appear as a legitimate browser.
- **Cost-Effective:** Cuts costs by ~75% compared to premium solutions like Multilogin or GoLogin.
- **DVSA-OBS Optimized:** Tailored specifically for the workflows and patterns of the DVSA booking system.
- **Stealth Mode:** Implements intelligent delays, human-like mouse movements, and randomized user-agent strings to avoid bot detection.
- **Lightweight & Efficient:** Built for performance and reliability without the bloat of large commercial platforms.

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your machine:
- **Python 3.8+**
- **Google Chrome** browser
- **pip** (Python package manager)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/dvsa-obs-automation.git
    cd dvsa-obs-automation
    ```

2.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Configure the application:**
    - Update `config.json` with your DVSA credentials and preferences
    - Adjust browser and automation settings as needed

### Usage

Run the main script:
```bash
python main.py
