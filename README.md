# Simple Bike Sales Dashboard: Finding Our Best Customers

## 📌 Project Overview
Have you ever wondered who is most likely to buy a bicycle? In this project, I took a messy list of raw customer data and turned it into an easy-to-read, interactive dashboard using **Microsoft Excel**. 

The goal of this project is simple: to help a bike store look at their customers' age, income, region, and daily commute, so they can figure out who their best buyers are and how to advertise to them more effectively.

### 🖼️ Dashboard Preview
<img width="500" height="223" alt="Bike Sales Dashboard" src="https://github.com/user-attachments/assets/1966f0d2-9cb9-4ecc-8628-6f3b615173fc" />
Excel Project Dataset from Alex the Analyst Youtube Channel

*Figure 1.0: My interactive Excel dashboard showing customer trends at a glance.*

---

## 🛠️ Tools & What I Did
* **Excel Power Query:** Used to import, clean up, and organize the data.
* **Excel Formulas:** Used simple logic to sort people into categories (like grouping ages into "Middle Age" or "Adolescent").
* **Pivot Tables & Charts:** Used to automatically summarize thousands of rows of data into clean charts.
* **Interactive Slicers:** Added clickable buttons (filters) on the left side so anyone can click around and see the charts update instantly.

---

## 🧹 Cleaning the Data (Making it Usable)
Before making the charts, the data was a bit of a mess. Here is how I fixed it so the reports would be 100% accurate:
1. **Fixing Typos:** Changed confusing abbreviations like `M` to `Married` and `S` to `Single` so it’s easy for anyone to read.
2. **Fixing Numbers:** Standardized the income column into proper currency formatting ($).
3. **Grouping People:** Instead of looking at random individual ages and distances, I grouped them into neat categories like **Age Brackets** (Adolescent, Middle Age, Old) and **Commute Distance** (0-1 Miles, 1-2 Miles, etc.).

---

## 📊 4 Simple Things We Learned From the Data

By looking at the finished dashboard in image_384627.png, we can easily spot four major trends:

### 1. Income Matters (Especially for Men)
* **What the data says:** People who actually bought a bike (`Yes` in the charts) have a higher average income than those who didn't (`No`). For men who bought bikes, the average income is around **$60,124**.
* **Business Advice:** When running ads, target neighborhoods or platforms where the average income is around $55,000 or higher so we don't waste money on ads.

### 2. Middle-Aged People are Our Best Customers
* **What the data says:** A massive **70% of all bikes were bought by Middle-Aged customers**. Young adults (Adolescents) made up the smallest group at just 11%.
* **Business Advice:** Put most of the marketing budget into targeting middle-aged professionals. Use pictures and stories that relate to them in our advertisements.

### 3. Bikes are Used for Short Trips, Not Long Commutes
* **What the data says:** Bike sales are highest for people who live very close to work (**0 to 1 mile away**). Once someone's commute is longer than 5 miles, they rarely buy a bike.
* **Business Advice:** Don't market these as "long-distance commuter bikes." Instead, advertise them for quick neighborhood errands, local fitness, or short weekend rides.

### 4. North America is Our Biggest Market
* **What the data says:** **North America accounts for 51% of all bike sales**, while Europe sits at 30% and the Pacific region is at 19%.
* **Business Advice:** Make sure our warehouses in North America always have plenty of bikes in stock so we never run out of our best-selling region.

---

## 🚀 How to Try the Dashboard Yourself
1. Download the `.xlsx` file from this repository.
2. Open it in Microsoft Excel.
3. Click on the blue buttons on the left side (**Marital Status, Education, Region**). Watch how all the charts automatically change and adjust depending on what you click!
