# 🏡 Airbnb Listings Analysis – NYC 2025

This project analyzes Airbnb listings in New York City using Python for data preprocessing and Power BI for visualizations. It explores pricing patterns, room types, neighborhood impacts, and review behaviors to provide actionable insights for both customers and hosts.

---

## 📌 Objective

To analyze NYC Airbnb listings to:
- Understand price trends
- Determine which features impact listing prices and popularity
- Provide insights and visualization tools for better decision-making

---

## 📂 Dataset Overview

The dataset contains information on:
- `name`, `host_name`
- `neighbourhood`, `room_type`
- `price`, `minimum_nights`
- `number_of_reviews`, `last_review`
- And other related variables

---

## 🧹 Data Cleaning Steps

- Filled missing values (e.g., `reviews_per_month` filled with 0)
- Converted date columns like `last_review` to `datetime`
- Removed duplicate records
- Converted data types appropriately

---

## 📊 Key Insights

1. **Price Distribution**
   - Highly right-skewed
   - Most listings priced under $500

2. **Room Type Impact**
   - Entire homes/apartments are most expensive
   - Private rooms are more affordable and commonly listed

3. **Neighborhood Trends**
   - Some neighborhoods dominate the listing count
   - Significant variation in average pricing by area

4. **Minimum Night Stay**
   - Most hosts require fewer than 10 minimum nights

5. **Review Patterns**
   - High-review listings tend to be affordable and well-located

---

## 📈 Power BI Dashboard Highlights

To enhance data exploration, a Power BI dashboard is recommended with:
- **Price Slider Filter** – Dynamically filter listings by budget
- **Map View** – Geolocation of listings with:
  - Bubble size = number of reviews
  - Color = room type
- **Bar Chart** – Average price by neighborhood
- **Pie Chart** – Room type distribution
- **Cards** – Key stats (Total Listings, Avg Price, Avg Reviews)

---

## 🛠 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Power BI (for dashboard and interactivity)

---

## 📌 Next Steps

- Export cleaned data as `.csv`
- Import into Power BI
- Build the recommended dashboard for exploratory analysis

---

## 📁 Files Included

- `Air_bnb.ipynb` – Full code for data cleaning and analysis
- `Airbnb_Project_Report.pdf` – Summary report
- `Airbnb_Listings_Analysis_NYC_2025.pdf` – Supplementary insights

---

## 🙌 Contributions

If you'd like to enhance the visualizations, add predictive modeling, or expand the analysis to other cities, feel free to fork and contribute!
