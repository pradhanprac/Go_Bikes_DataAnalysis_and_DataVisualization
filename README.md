# 🚴 Ford GoBike System Data Exploration  

## 📌 Overview  
This project explores data from the **Ford GoBike** bike-sharing system, which operated in the **San Francisco Bay Area in 2019**. The analysis focuses on identifying **riding patterns, user behaviors, and trip characteristics** by examining the dataset and uncovering key insights.

## 📂 Project Structure  

## 📊 Dataset Details  
The dataset consists of **183,412 bike ride records** from the **Ford GoBike** system. It contains **16 original features**, including:
- `duration_sec`, `start_time`, `end_time`
- `start_station_id`, `start_station_name`, `start_station_latitude`, `start_station_longitude`
- `end_station_id`, `end_station_name`, `end_station_latitude`, `end_station_longitude`
- `bike_id`, `user_type`, `member_birth_year`, `member_gender`, `bike_share_for_all_trip`

After **data cleaning and feature engineering**, the dataset was transformed into **11 key features**, adding:
- **`day_of_week`**: Extracts the day of the week from `start_time`.  
- **`start_hour`**: Stores the hour of the day from `start_time`.  
- **`time_of_day`**: Categorizes trips into different times of the day.  
- **`duration_min`**: Converts trip duration into minutes.  
- **`user_age`**: Calculates the user's age from `member_birth_year`.  
- **`user_age_bin`**: Groups users into different age categories.  

## 🎯 Key Findings from the Analysis  

The study uncovered distinct **usage patterns between subscribers and casual customers**:
- **Trip Frequency**: Most trips occurred on **Thursdays**, but this trend was consistent across both **subscribers and customers**.  
- **Usage Behavior**:  
  - **Subscribers** primarily used bikes on **weekdays (Monday-Friday)**, indicating usage for **commuting purposes**.  
  - **Customers** displayed **consistent bike usage throughout the week**, with a **significant increase on weekends (Saturday & Sunday)**.  
- **Trip Duration**:  
  - **Subscribers' average ride duration** was around **10-11 minutes**.  
  - **Customers' rides were significantly longer**, averaging **23-24 minutes** per trip.  
  - **Customers were more likely to take trips exceeding 60 minutes**, while **subscribers typically had shorter trips**.  
- **Trip Start Time**:  
  - **Subscribers started trips mostly at 8 AM and 5 PM**, aligning with **work commute hours**.  
  - **Customers initiated trips more frequently in the afternoon**, with a **peak at 5 PM**.  
- **Weekend vs. Weekday Patterns**:  
  - **Trips during weekends (Saturday & Sunday) lasted longer** than those on weekdays, possibly due to leisure biking.  

## 📢 Key Insights   
1️⃣ **What time of day and which day of the week see the most rides?**  
2️⃣ **How long do trips typically last on average?**  
3️⃣ **Does trip duration differ between subscribers and customers?**  

Findings indicated that **customers take longer rides than subscribers across all days and times of the week**, reinforcing the observation that **subscribers use bikes primarily for commuting**, whereas **customers use them for leisure activities**.  

## 📊 Visualizations  
The following visualizations were used to present insights effectively:  
- **Boxplots and Histograms**: Used for **outlier detection** and understanding trip duration distribution.  
- **Scatter Plots & Bar Charts**: Helped compare **subscriber vs. customer behavior** across weekdays and different hours.  
- **Heatmaps**: Highlighted correlation patterns between variables.  

## 🚀 How to Run the Notebook  
### **🔹 Prerequisites**  
Ensure the following dependencies are installed:  
```bash
pip install pandas numpy matplotlib seaborn jupyter

🔹 Running the Notebook
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
Navigate to the directory:
cd your-repo-name
Launch Jupyter Notebook:
jupyter notebook
Open the Exploratory_data_analysis.ipynb file and run the cells.
🏆 Conclusion
This Exploratory Data Analysis (EDA) highlights riding trends, user behaviors, and trip patterns from the Ford GoBike dataset. The results show a clear distinction between how subscribers and customers use the service, with subscribers commuting during peak hours and customers engaging in leisure rides. The insights gained from this analysis can support urban transportation planning and business strategies for bike-sharing services.

.

🔗 Connect with Me
If you have any questions, feel free to reach out or contribute to this project! 🚀

🔗 LinkedIn: linkedin.com/in/prachi-pradhan2612

