# AI Smart Home Appliances (Targeting the Improvement of Teenagers' Habits)
A smart home control system built in Python, designed for teenage users. It allows controlling devices such as lights and air conditioning via webhook requests. Developed as a semester project in a data structure course, the system focuses on comfort-based automation with clear and simple logic.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Resources](#resources)

## Introduction
This project demonstrates how to build a Python-based IoT (Internet of Things) application for smart home control, specifically tailored for teenagers. It integrates with a Home Assistant API using HTTP requests to toggle devices like lights and temperature control units, based on environmental comfort.

## Features
💡 Lighting Control - Automatically toggle lights based on brightness comfort.<br>
🌡️ Temperature Control - Control heating/cooling devices depending on indoor temperature.<br>
📊 Google Sheets Logging - Log device status, timestamps, and user commands.<br>
🧪 Webhook API Integration - Trigger actions using secure HTTP POST requests.<br>
📈 Data-Driven Feedback - Use spreadsheet analysis to adjust automation thresholds.<br>

## Usage
▶️ Run the notebook or Python script to trigger the smart home functions:
```text
# Turn light ON
turn_11_on()

# Turn light OFF
turn_11_off()

# Activate temperature device
turn_12_on()

# Deactivate temperature device
turn_12_off()
```
All functions send POST requests to the designated Home Assistant webhooks using an authorization token.

## Resources
[Project Description PDF](https://github.com/ethanlin1126/DS/blob/main/%E6%99%BA%E8%83%BD%E5%AE%B6%E9%9B%BB.pdf)<br>
[Google Colab Code](https://colab.research.google.com/drive/1PGRkGe_Pj9mGePHu_de3hOsz_6pHqKYb#scrollTo=yBXLAZWTOE9X)<br>
[Google Sheet Log](https://docs.google.com/spreadsheets/d/16NhAOWn_yq4i3WssKDXiHmqfN6mCyzqN6O7jFXVFqeQ/edit#gid=0)
