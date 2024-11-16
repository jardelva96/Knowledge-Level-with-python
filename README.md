# Knowledge Level Chart - Python Fullstack Desktop Application

This is a **Python Fullstack Desktop Application** that generates and displays a "Knowledge Level by Technology" chart. The application uses **Matplotlib** for chart generation and **Tkinter** for the desktop graphical user interface (GUI).

## 📋 Features
- Generates a **horizontal bar chart** based on customizable data.
- Desktop application built with **Tkinter**.
- Reads data from a JSON file for easy configuration.
- Saves the generated chart as an image file (`knowledge_chart.png`).
- Clean and responsive UI.

---

## 🛠️ Technologies Used
- **Python**
- **Matplotlib** (Chart generation)
- **Tkinter** (GUI)
- **PIL** (Image handling)
- JSON for data configuration

---

## 📂 Project Structure

```plaintext
project/
├── app/
│   ├── backend.py      # Backend to process data and generate the chart
│   ├── frontend.py     # Desktop interface with Tkinter
│   ├── data.json       # Data used to create the chart
├── venv/               # Python virtual environment (optional)
└── requirements.txt    # Python dependencies
