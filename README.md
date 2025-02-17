# 🌍 Beyond Borders: Unpacking Canada’s Changing Travel Trends

## 📌 Overview
This project explores the shifting travel patterns in Canada from 2020 to 2024, focusing on the impact of the COVID-19 pandemic on cross-border movements. By analyzing Statistics Canada data, we uncover trends in traveler demographics, transportation modes, and regional travel dynamics.

## 🔥 Motivation
The COVID-19 pandemic brought unprecedented disruptions to global travel. We sought to understand:  
- How travel patterns changed over time.  
- Which regions were most affected.  
- The demographics of travelers post-pandemic.  
- The role of different transportation modes in recovery.  

## 📊 Datasets Used (link : https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=2410005001 )
We analyzed a dataset from Statistics Canada containing **over 2.7 million records**, narrowed down to a **representative sample of 142,000 entries** for detailed exploration. The dataset included:  
- **Date** (Year, Month)  
- **Traveler Characteristics** (Resident type, transport mode)  
- **Geography** (Provinces, security level)  
- **Traveler Type** (Tourists, business travelers, residents)  
- **Number of Travelers**  

## 🛠 Methodology & Techniques
To extract meaningful insights, we performed:  
- **Data Cleaning & Preprocessing**: Handling missing values, restructuring columns.  
- **Exploratory Data Analysis (EDA)**: Identifying key trends.  
- **Time Series Analysis**: Observing travel fluctuations from 2020-2024.  
- **Clustering (K-Means + TF-IDF)**: Categorizing travelers by transport modes.  
- **Classification (Random Forest Model)**: Predicting traveler types.  

## 📈 Key Findings
### 1️⃣ Travel Trends Over Time 📅  
- Travel **plummeted in early 2020** due to COVID-19 lockdowns.  
- **Gradual recovery in 2021** with increased travel confidence.  
- By **mid-2024, travel exceeded pre-pandemic levels** due to economic rebounds and global mobility shifts.  

### 2️⃣ Regional Insights 🏙  
- **Ontario**: The busiest hub with sharp fluctuations.  
- **British Columbia**: A steady performer due to international traffic.  
- **Quebec & Alberta**: Consistent travel linked to business and student movements.  
- **Northern Territories**: Lowest travel volumes, driven by seasonal spikes.  

### 3️⃣ Traveler Demographics 👥  
- **Canadian Residents**: Dropped to **45.3% in 2023**, rebounding to **57.1% in 2024**.  
- **International Visitors**: Peaked in **2023 at 22.2%**, driven by “revenge travel.”  
- **U.S. Visitors**: Remained stable (~15-17%).  

### 4️⃣ Security Trends 🔐  
- **Ontario & Quebec** had the highest **high-security** enforcement levels.  
- **British Columbia** showed a mix of **high- and low-security zones**.  

### 5️⃣ Transport Modes & Cluster Analysis ✈️🚗🚢  
- **Air Travel**: Dominated international movement.  
- **Land Travel**: Showed steady recovery post-pandemic.  
- **Water Travel**: Remained niche but stable.  

## 🖥 Technologies Used
- **Programming**: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- **Data Processing**: SQL for dataset querying  
- **Visualization**: Tableau & Matplotlib for dashboards and graphs  
- **Modeling**: K-Means clustering, Random Forest classification  

## 🔮 Future Improvements

- Expanding analysis beyond 2024 to track long-term travel trends.
- Incorporating social media sentiment analysis to correlate with travel behaviors.
- Developing predictive models to forecast future travel patterns.

## Contributors

Navya: Led time-series analysis, clustering transport data.
Gulshan: Structured the dataset, analyzed COVID-19 impact, security trends, and wrote the data story.
Both: Worked on implementing Random Forest classification.
