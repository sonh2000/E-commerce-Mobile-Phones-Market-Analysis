# 📱 E-commerce Mobile Phones Market Analysis (Amazon & Jumia)

## 📌 Overview
This project explores the **Egyptian e-commerce mobile phone market** by scraping product data from **Amazon** and **Jumia**, cleaning and preprocessing the dataset, and analyzing it with **Power BI**.  
The goal is to uncover **market trends, brand positioning, and pricing strategies** to demonstrate skills in **Python, Excel, and Power BI**.

---

## 📂 Data Workflow
- **Data Collection**  
  - Used **Python (BeautifulSoup, Requests)** to scrape product listings.
  - the code is here [`scraping_and_cleaning.ipynb`](amazon_smartphones.ipynb)
  - and here [`scraping_and_cleaning.ipynb`](juimia_smartphones.ipynb)
  - Extracted: product name, brand, price, storage/RAM, and platform (Amazon or Jumia).  

- **Data Cleaning & Preprocessing**  
  - Cleaned with **Pandas** (removed duplicates, handled missing values, standardized brand names).  
  - Exported to **Excel** for quick validation.  
  - Final dataset loaded into **Power BI**.  

- **Data Modeling & Measures**  
  - Built relationships between product attributes.  
  - Created multiple **DAX measures** (average price, count of phones, platform share, price vs spec KPIs).  

---

## 📊 Dashboard Pages
The Power BI dashboard contains **4 interactive pages**:

1. **Market Overview** – KPIs, total listings, price distribution.  
2. **Brand Analysis** – Market share, avg. price per brand, segment comparisons.  
3. **Platform Comparison** – Amazon vs Jumia differences in pricing and availability.  
4. **Specs vs Price Analysis** – How features (RAM, storage) affect pricing.  

---

## 🔍 Key Insights
- **Amazon vs Jumia**: Amazon lists more premium models; Jumia offers more budget options.  
- **Brand Analysis**: Apple dominates high-end; Samsung/Xiaomi strong in mid-range; Infinix targets budget buyers.  
- **Specs vs Price**: Strong correlation between specs (RAM, storage) and price, with brand-based exceptions.  

---

## 🧩 Skills Demonstrated
- **Python** – Web scraping with BeautifulSoup, data cleaning with Pandas.  
- **Excel** – Data validation and exploration.  
- **Power BI** – Data modeling, DAX measures, dashboard design.  
- **Business Analysis** – Market research, competitor comparison, actionable insights.  

---

## 🚀 How to Use
1. Download the `.pbix` file from this repo.  
2. Open in **Power BI Desktop**.  
3. Use slicers and filters to interact with the dashboard (by brand, platform, or price range).  

---

## 📸 Dashboard Preview
###                                       Market Overview
![Market Overview](https://github.com/sonh2000/E-commerce-Mobile-Phones-Market-Analysis/blob/main/visu1.png?raw=true)
###                                       Brand_analysis
![brand_analysis](https://github.com/sonh2000/E-commerce-Mobile-Phones-Market-Analysis/blob/4d5410aa7b3ce5b8e03131a7320c9d34e87bc95f/visual%203%20.png)
###                                       platform_comparison
![platform_comparsion](https://github.com/sonh2000/E-commerce-Mobile-Phones-Market-Analysis/blob/main/visu1.png?raw=true)
###                                       spec vs analysis
![spec vs analysis](https://github.com/sonh2000/E-commerce-Mobile-Phones-Market-Analysis/blob/4d5410aa7b3ce5b8e03131a7320c9d34e87bc95f/visual2%20.png)


## 📬 Contact  
- Email: yasserhassen98@gmail.com
- LinkedIn: [linkedin.com/in/yourprofile](www.linkedin.com/in/hassan-yasser-2000hh)  
- GitHub: [github.com/yourusername](https://github.com/sonh2000)  
