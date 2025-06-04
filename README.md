# TimeWarp — Personal Digital Time Tracker

**TimeWarp** is a simple Python tool that helps you understand how you spend your time on your computer by tracking your active window usage on Linux. It categorizes your activity into areas like Work, Social, Entertainment, Browsing, and Writing, so you can get insights into your daily digital habits.

---

## Features
* Tracks your active window every 10 seconds using `xdotool` (Linux only).
* Categorizes your activity based on app names and window titles.
* Saves all tracked data locally in an SQLite database.
* Displays an easy-to-understand dashboard showing your activity by category and time of day.
* Clean, modular code ideal for learning and showcasing on your resume.


## How It Works

TimeWarp continuously monitors which window is active on your screen every 10 seconds. It saves the information locally, categorizes it into meaningful groups, and when you stop the tracker, it presents a visual summary of your digital time use.

---

## Project Structure

```
timewarp/
├── main.py               # The main script to start tracking and show dashboard
├── tracker/              # Modules handling activity tracking and categorization
│   ├── __init__.py
│   ├── activity_tracker.py
│   └── categorizer.py
├── ui/                   # Dashboard visualization code
│   ├── __init__.py
│   └── dashboard.py
├── data/                 # Folder where activity data is stored
├── requirements.txt      # Python dependencies list
└── README.md             # This document
```


## Why Use TimeWarp?

TimeWarp is a practical, hands-on project that combines system-level integration, data storage, and visualization. It’s a great way to demonstrate skills in Python programming, working with OS tools, databases, and plotting libraries — all valuable for a software developer role in today’s job market.

## Contributions

If you find bugs or have ideas for improvement, feel free to open issues or submit pull requests. Contributions are always welcome.

---
