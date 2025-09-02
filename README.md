# Zomato-Data-Analysis-project

Here’s a **professional and detailed README.md** draft for your Zomato Data Analysis project. I’ve highlighted everything pointwise for clarity and professionalism:

---

# Zomato Data Analysis Mini Project

## 📌 Project Overview

This project focuses on analyzing restaurant data from **Zomato** to uncover insights related to customer preferences, restaurant performance, and dining patterns. Using Python, Pandas, Matplotlib, and Seaborn, we perform **data cleaning, exploration, and visualization** to answer business-oriented questions.

The dataset includes **148 restaurants** with features such as restaurant name, rating, votes, availability of online orders, table booking options, cost for two, and restaurant type.

---

## Objectives

The key objectives of this project are:

* Clean and preprocess raw Zomato dataset for analysis.
* Explore patterns in restaurant ratings, customer votes, and pricing.
* Visualize the distribution of restaurant types and dining preferences.
* Derive meaningful business insights to improve customer experience.

---

## Dataset Details

* **File Name:** `Zomato data .csv`
* **No. of Records:** 148
* **Columns:**

  * `name` → Restaurant name
  * `online_order` → Availability of online orders (Yes/No)
  * `book_table` → Availability of table booking (Yes/No)
  * `rate` → Average customer rating
  * `votes` → No. of customer votes
  * `approx_cost(for two people)` → Approximate cost for two people
  * `listed_in(type)` → Type of restaurant (e.g., Buffet, Café, etc.)

---

## Tools & Technologies Used

* **Programming Language:** Python
* **Libraries:**

  * `NumPy` → Numerical computations
  * `Pandas` → Data cleaning and manipulation
  * `Matplotlib` → Data visualization
  * `Seaborn` → Statistical data visualization
* **Notebook Environment:** Jupyter Notebook

---

## Data Preprocessing Steps

1. **Loading Dataset:** Imported the CSV file into a Pandas DataFrame.
2. **Handling Missing Values:** Checked and treated null values.
3. **Data Type Conversion:** Converted `rate` column into numerical format.
4. **Cleaning:** Removed inconsistencies and standardized values.

---

## Key Analyses & Visualizations

✔️ Distribution of **restaurant types** based on customer orders.
✔️ Analysis of **online ordering vs offline dining preference**.
✔️ Impact of **table booking availability** on ratings.
✔️ Relationship between **customer votes and ratings**.
✔️ Effect of **approximate cost** on restaurant popularity.
✔️ Visualization of **top-rated restaurants**.

---

## Insights Derived

* Majority of customers prefer **Buffet and Café-style** restaurants.
* Restaurants with **table booking options** generally receive higher ratings.
* Online ordering services have a **direct impact on customer engagement**.
* Customer votes strongly correlate with **restaurant visibility and trust**.
* Mid-range pricing tends to attract the most customers.

---

## 🚀 How to Run the Project

1. Clone the repository from GitHub:

   ```bash
   git clone <your-repo-link>
   ```
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook "zomato data analysis mini project.ipynb"
   ```
4. Run cells step by step to view data analysis and visualizations.

---

## 📌 Project Highlights

* ✅ Clean and well-structured data preprocessing.
* ✅ Business-driven analysis of restaurant data.
* ✅ Clear and insightful visualizations with **Seaborn & Matplotlib**.
* ✅ Easy-to-run Jupyter Notebook for reproducibility.
* ✅ Real-world use case for **food-tech & restaurant industry**.

---

## 📈 Future Enhancements

* Apply **Machine Learning models** to predict restaurant ratings.
* Perform **sentiment analysis** on customer reviews (if text data is available).
* Expand dataset with **location-based analysis** for deeper insights.
* Build a **dashboard (using Plotly/Streamlit)** for interactive exploration.

