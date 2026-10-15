# Deployment Guide

This document describes how to deploy and run the service.

## Prerequisites
- Python 3.11+
- Virtual environment (`venv`)

## Deployment Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/abhinav00anand/automaintainer-sandbox-test.git
   ```
2. Set up virtual environment and install dependencies:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Or .venv\Scripts\activate on Windows
   pip install -e .
   ```
3. Verify configuration in `.automaintainer.yml`.
