# Athens Airbnb Analysis 🏠

## 📌 Project Overview
This project is an exploratory data analysis (EDA) of **Athens Airbnb listings**.  
The goal is to uncover insights about:
- Popular neighborhoods  
- Pricing patterns  
- Availability of listings  
- Hosts and property types  

## 📊 Dataset
- `listings` table: id, name, neighbourhood, room_type, price, minimum_nights, number_of_reviews, host_id

## 🔍 Tools & Technologies
- **SQL** – for querying and cleaning data
- **Tableau** – for data visualization & interactive dashboards

## 🛠️ Steps of the Project
1. **Data Extraction & Cleaning** – Using SQL to filter, clean, and prepare data
2. **Exploratory Data Analysis (EDA)** – Analyzing patterns in listings, pricing, and neighborhoods
3. **Visualization** – Creating charts & dashboards in Tableau
4. **Insights & Recommendations** – Summarizing findings for stakeholders

## 📈 Sample Insights
- Most listings are concentrated in central neighborhoods  
- Prices vary by property type, with entire apartments being the priciest  
- Hosts with multiple listings dominate popular areas  

## 📂 Project Structure

## 📊 Query Results

- - **Neighbourhood Count** → [data/neighbourhood_counts.csv](data/neighbourhood_counts.csv)
- **Average Price by Neighbourhood** → [data/neighbourhood_avg_price.csv](data/neighbourhood_avg_price.csv)
- **Room Type Price** → [data/room_type_avg_price.csv](data/room_type_avg_price.csv)
- **Room Type Availability** → [data/room_type_avg_availability.csv](data/room_type_avg_availability.csv)

## 📉 Visualizations

### 1. Average Price by Room Type
![Room Type Avg Price](visuals/room_type_avg_price.png)

### 2. Average Availability by Room Type
![Room Type Avg Availability](visuals/room_type_avg_availability.png)

### 3. Average Price by Neighbourhood
![Neighbourhood Avg Price](visuals/neighbourhood_avg_price.png)

### 4. Listings Count by Neighbourhood
![Neighbourhood Count](visuals/neighbourhood_count.png)
