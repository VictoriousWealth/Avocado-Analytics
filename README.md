# 🥑 Avocado Analytics Dashboard

An interactive web dashboard built with **Dash** and **Python** to visualize avocado prices and sales trends across the United States between 2015 and 2018.

---

## 🚀 Features

- 📈 View the **average price** and **total volume** of avocados over time.
- 🌎 **Filter by region** (Albany, Boston, Los Angeles, etc.).
- 🥑 **Filter by type** (conventional or organic avocados).
- 🗕️ **Select a date range** to zoom in on specific time periods.
- 🎨 Simple and clean UI styled with custom fonts and minimal design.
- ⚡ Real-time graph updates based on user selections.

---

## 🛠️ Built With

- **Python**  
- **Dash (by Plotly)**  
- **Pandas**  
- **HTML/CSS** (embedded in Dash components)

---

## 📂 Project Structure

```bash
.
├── app.py         # Main Dash app
├── avocado.csv    # Dataset (2015-2018 avocado sales in the US)
```

---

## 📊 Dataset

- Sourced from Kaggle: [Avocado Prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)
- Contains information on avocado sales such as:
  - **Average price**
  - **Total volume sold**
  - **Region**
  - **Type** (organic or conventional)
  - **Date**

---

## 🧠 How It Works

- Load avocado sales data using **Pandas**.
- Preprocess and sort data by **date**.
- Build an interactive layout with **Dash** components:
  - **Dropdown menus** for region and type.
  - **Date picker** for selecting date range.
- Dynamically update graphs based on user selections using **Dash Callbacks**.
- Visualize:
  - Line graph of **Average Price** over time.
  - Line graph of **Total Volume Sold** over time.

---

## 🚀 Running Locally

1. Clone the repository:

```bash
git clone https://github.com/VictoriousWealth/Avocado-Analytics.git
cd Avocado-Analytics
```

2. Install dependencies:

```bash
pip install pandas dash
```

3. Run the app:

```bash
python app.py
```

4. Visit `http://127.0.0.1:8050/` in your browser.

---

## 🌟 Future Improvements

- Add multi-region comparison.
- Enable download of filtered data as CSV.
- Deploy to a cloud platform (e.g., Heroku, AWS, Render).

---

## 💋 Contact

Feel free to connect with me:

- [LinkedIn](https://www.linkedin.com/in/nick-efe-oni)
- ✉️ Email: efeoni10@gmail.com

---

_Thanks for visiting Avocado Analytics! 🥑_

---
