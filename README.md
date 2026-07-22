## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/data-usage-tracker.git
   cd data-usage-tracker
   ```

2. **Install required dependencies:**
   The only external dependency is `psutil`. Install it via pip:
   ```bash
   pip install psutil
   ```

## 💻 Usage

To run the application, execute the main Python script from your terminal:

```bash
python data_tracker_gui.py
```

**How it works:**
1. Upon launch, a small window will appear displaying your current Upload, Download, and Total Used statistics.
2. The app will immediately create a `data_usage_log.csv` file in the same directory and begin writing network states every second.
3. Click the **"View Log"** button to open a new window and review your usage history directly within the application.

## 📁 File Structure

```text
MOBILE DATA USAGE TRACKER/
│
├── data_tracker_gui.py   # Main application script containing the Tkinter GUI and tracking logic
├── data_usage_log.csv    # Auto-generated log file (created on first run)
└── README.md             # Project documentation
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
Feel free to check the [issues page](https://github.com/yourusername/data-usage-tracker/issues) if you want to contribute.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.# DATA-USAGE-TRACKER-
