# 🎮 Nintendo Handheld Price Tracker 📊 

## ✨ Description
The **Handheld Price Tracker** is a Python-based tool designed to track the current average prices of handheld gaming consoles using **web scraping**. It provides insightful visualizations of trends for consoles in **New**, **Used**, and **Faulty/For Parts** conditions. This tool is ideal for gamers, collectors, and enthusiasts looking to stay informed about pricing trends in the second-hand gaming market.

---

### Handheld Consoles Tracked

#### 🔵 **Nintendo DS Family**
- Nintendo DS Lite

#### 🔴 **Nintendo 2DS Family**
- Nintendo 2DS
- New Nintendo 2DS XL

#### 🟢 **Nintendo 3DS Family**
- Nintendo 3DS XL
- New Nintendo 3DS
- New Nintendo 3DS XL

#### 🟡 **Gameboy Advance Family**
- Gameboy Advance
- Gameboy Advance SP

#### 🔴 **Nintendo Switch Family**
- Nintendo Switch

---

### 🚀 Key Features
- **📊 Interactive Visualizations**: Displays pricing trends using dynamic boxplots for easy analysis of price ranges by console and condition.
- **🔄 Condition-Based Tracking**:
  - **🆕 New**: Unused, unopened handhelds.
  - **🔄 Used**: Pre-owned consoles in working condition.
  - **⚠️ Faulty / For Parts**: Consoles that require repairs or are sold for parts.
- **❌ No Special Editions**: Focuses on standard models to avoid skewed pricing due to collector editions.
- **⏳ Loading Progress Feedback**: Provides real-time progress updates for both overall and console-specific data fetching.
- **🌐 Dynamic Scraping**: Extracts up-to-date pricing information directly from eBay.

---

## 🛠️ Technologies Used
- **Python**: The main programming language for data scraping and visualization.
- **Libraries**:
  - `requests`: For making HTTP requests to scrape data.
  - `BeautifulSoup`: For parsing and extracting relevant pricing information from HTML pages.
  - `pandas`: For structuring and processing data.
  - `plotly.express`: For creating interactive and visually appealing plots.
  - `tkinter`: For GUI-based loading progress bars.
  - `threading`: For managing asynchronous tasks and ensuring a responsive interface.

---

## 📋 Usage
1. Clone the repository.
2. Install the required dependencies:
   ```bash
   pip install requests beautifulsoup4 pandas plotly tqdm
   ```
3. Run the script:
   ```bash
   python handheld_price_tracker.py
   ```
4. A `tkinter` GUI will appear showing the loading progress for each console and condition. Upon completion, an interactive Plotly chart will open displaying pricing trends.

---

## 📊 Output
### Visualizations
- Interactive **boxplots** to visualize price ranges and trends for:
  - Different console models.
  - Conditions: **New**, **Used**, and **Faulty/For Parts**.
  
---

## ✨ Future Improvements
- **Real-Time Updates**: Enable periodic data refresh for continuously updated pricing information.
- **Additional Platforms**: Expand to include Sony PSP, PS Vita, or Sega handhelds.
- **Regional Support**: Allow filtering by eBay regions beyond the UK.
- **Export Options**: Add functionality to save visualizations as images or export data to CSV files.

---
