# Python, Anaconda & Jupyter Notebook — Installation Guide

This document describes the steps taken to set up the Python development environment, including Python itself, Anaconda Navigator, and Jupyter Notebook.

---

## Part 1: Python Installation (Windows)

### Step 1 — Download Python
- Visited the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
- Downloaded the latest version (Python 3.13.0 at the time of installation)

### Step 2 — Installation Options
- Ran the downloaded installer
- Checked **both** boxes:
  - ✅ Install launcher for all users
  - ✅ **Add Python to PATH** *(important for command-line access)*
- Clicked **"Install Now"**

### Step 3 — Allow Permissions
- When prompted by Windows User Account Control, clicked **"Yes"** to allow the installation to proceed

### Step 4 — Disable Path Length Limit
- After installation completed, clicked **"Disable path length limit"** to prevent issues with directories longer than 260 characters
- Clicked **Close** to exit the installer

---

## Part 2: Anaconda Navigator Installation

Anaconda is a Python distribution pre-bundled with popular data science libraries, tools, and the Jupyter Notebook environment.

### Step 1 — Download Anaconda
- Visited the official Anaconda download page: [https://www.anaconda.com/download](https://www.anaconda.com/download)
- Clicked **"Skip Registration"** and then clicked **"Download"** to download the Windows installer

### Step 2 — Run the Installer
- Opened the downloaded `.exe` file
- Clicked **Next** on the welcome screen

### Step 3 — License Agreement
- Read the licensing terms and clicked **"I Agree"**

### Step 4 — Select Installation Type
- Selected **"Just Me"** (recommended for personal use; "All Users" requires Administrator privileges)
- Clicked **Next**

### Step 5 — Choose Installation Folder
- Selected a destination directory (no spaces or Unicode characters in the path, as required)
- Clicked **Next**

### Step 6 — Advanced Options
- Configured whether to add Anaconda to the PATH environment variable
- Configured whether to register Anaconda as the default Python interpreter

### Step 7 — Install
- Clicked **Install** to begin installation
- Optionally clicked **Show Details** to monitor package installation progress

### Step 8 — Complete the Installation
- Clicked **Next** on the completion screen
- Skipped the optional PyCharm installation by clicking **Next**
- Unchecked optional tutorial/resource checkboxes and clicked **Finish**

---

## Part 3: Launching Jupyter Notebook

Jupyter Notebook comes pre-installed with Anaconda. No additional installation was needed.

### Step 1 — Open Anaconda Navigator
- Launched **Anaconda Navigator** from the Start Menu

### Step 2 — Launch Jupyter Notebook
- Located **Jupyter Notebook** in the Navigator home screen
- Clicked **Launch** — this opened Jupyter Notebook in the default web browser

### Step 3 — Create a New Notebook
- In the Jupyter file browser, navigated to the desired directory
- Clicked the **New** button and selected **Python 3**
- A new `.ipynb` notebook opened and was ready for writing and running Python code

---

## Notes

- **Python** was installed system-wide and added to PATH for easy terminal/command-line access
- **Anaconda** was used as the primary environment manager due to its built-in support for data science libraries (NumPy, Pandas, Matplotlib, etc.)
- **Jupyter Notebook** is used for writing and running Python code in an interactive, cell-based format — ideal for data analysis, ML experimentation, and academic work
- The `.ipynb` format supports live code, markdown text, equations, and visualizations in a single document

---

*Environment confirmed working. All tools successfully installed and launched.*
