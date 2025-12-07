# **QA Automation – Advantage Online Shopping**
<div align="center">

_A lightweight, Python-driven UI automation suite validating core purchase flows for the Advantage Online Shopping platform._

<br>

![Python](https://img.shields.io/badge/Python-3.9-3776AB?style=for-the-badge&logo=python)
![Selenium](https://img.shields.io/badge/Selenium-WebDriver-43B02A?style=for-the-badge&logo=selenium)
![Chrome](https://img.shields.io/badge/Browser-Chrome-4285F4?style=for-the-badge&logo=googlechrome)
![Status](https://img.shields.io/badge/STATUS-ACTIVE-8A2BE2?style=for-the-badge)

</div>

---

## ✨ Overview
This repository contains a minimal, high-clarity Selenium automation suite targeting the **Advantage Online Shopping (AOS)** demo application.  
The purpose: **clean, readable, business-critical UI tests** without framework bloat.

- Dynamic test data via **Faker**
- Modular locators + interaction helpers
- Direct, beginner-friendly structure
- Runs against **public** or **local** AOS deployments

---

## 🧪 Technology Stack
- **Python 3.9+** — main language
- **Selenium WebDriver** — UI automation
- **Google Chrome** — reference browser
- **Faker** — randomized user data
- **PostgreSQL (optional)** — for local AOS deployments
- **Standard Python modules** — unittest, time, etc.

---

## 🧩 Features
- Automated shopping workflows
- Randomized input data
- Simple project layout
- Clear separation of selectors, helpers, and tests
- Easily extended if you choose to evolve it later

---

## ⚙️ Requirements
- Python 3.9 or newer
- Google Chrome
- Selenium WebDriver
- Faker library

Install dependencies:
pip install -r requirements.txt

---

## ▶️ Running Tests
Run the full suite:
python aos_tests.py

Using a local AOS instance?  
Update the base URL inside `aos_methods.py`.

---

## 📝 Notes
This project is intentionally lightweight — designed for clarity, learning, and fast iteration.  
It can be expanded into a full automation framework (CI pipelines, reporting, screenshots, Page Object Model) if needed.

---

## 📄 License
MIT — free to use, modify, or extend.
