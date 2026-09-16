[README.md](https://github.com/user-attachments/files/32286475/README.md)
# ✈️ SkyRoutes Airline Route Profitability

> A Power BI and SQL-based data analytics project for analyzing airline route profitability, revenue, operational costs, passenger occupancy, and geographic performance.

---

## 📊 Project Overview

**SkyRoutes Airline Route Profitability** is a business-oriented data analytics project designed to identify profitable and underperforming airline routes.

The project analyzes airline flight data for **2025** using **SQL and Microsoft Power BI** to provide meaningful insights into:

- Route profitability
- Revenue and operational costs
- Passenger seat occupancy
- Monthly profit trends
- Domestic vs. international performance
- Revenue efficiency
- Geographic route distribution
- Aircraft performance

The final result is an interactive Power BI dashboard that helps users understand airline route performance and make data-driven decisions.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Identify the most profitable airline routes
- Find underperforming and loss-making routes
- Analyze revenue, cost, and profit by route
- Calculate passenger seat occupancy
- Study monthly profit trends
- Compare domestic and international route profitability
- Analyze revenue generated per minute of flight duration
- Visualize route origins geographically
- Provide interactive filtering through Power BI

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| 🐬 MySQL | Data analysis and SQL queries |
| 📊 Microsoft Power BI | Interactive dashboard and visualization |
| 📁 CSV | Dataset storage |
| 🖼️ Power BI Maps | Geographic route analysis |

---

## 📂 Dataset

The project uses a synthetic airline flight dataset containing **100,000 flight records** covering the year **2025**.

### Important Columns

- `FlightID`
- `RouteCode`
- `Origin`
- `Destination`
- `RouteType`
- `FlightDate`
- `FlightDurationMins`
- `AircraftType`
- `SeatsAvailable`
- `SeatsSold`
- `Revenue`
- `OperationalCost`
- `OriginLatitude`
- `OriginLongitude`
- `DestinationLatitude`
- `DestinationLongitude`

The dataset contains both **Domestic and International** routes along with multiple aircraft types.

---

# 🔎 SQL Analysis

The SQL analysis includes the following business questions:

### 1. Top 10 Most Frequent Routes
Identifies the routes with the highest number of flights.

### 2. Average Revenue, Cost & Profit by Route
Calculates average revenue, operational cost, and profit for each route.

### 3. Underperforming Routes
Identifies routes where the average profit is negative.

### 4. Seat Occupancy Percentage
Calculates passenger occupancy based on seats sold versus seats available.

### 5. Monthly Profit Trend
Analyzes revenue, cost, and profit across flight months.

### 6. Domestic vs International Profitability
Compares the profitability of domestic and international routes.

### 7. Revenue per Flight Minute
Ranks routes based on revenue generated per minute of flight duration.

---

# 📊 Power BI Dashboard

The Power BI dashboard contains two main pages.

## 🏠 Main Dashboard

The main dashboard provides a high-level overview of airline performance.

### Key Performance Indicators

- **Total Flights**
- **Total Revenue**
- **Total Cost**
- **Total Profit**
- **Average Occupancy**

### Visualizations

- Top 10 Most Profitable Airline Routes
- Total Profit by Flight Month
- Average Occupancy %
- Revenue vs Cost – Top 10 Routes

### Interactive Filters

- Aircraft Type
- Flight Month

---

## 🌍 Route Map & Geographic Analysis

The second dashboard page provides geographic analysis of airline route origins.

It includes:

- Route origin locations
- Route profitability
- Revenue information
- Geographic distribution
- Interactive route map
- Navigation back to the Main Dashboard

---

# 🖼️ Dashboard Preview

## Main Dashboard

![SkyRoutes Main Dashboard](SkyRoutes%20Airline%20Route%20Profitability%20Dashboard.png)

---

## Route Map & Geographic Analysis

![Route Map & Geographic Analysis](Route%20Map%20%26%20Geographic%20Analysis.png)

---

# 📈 Key Insights

The analysis provides several useful business insights:

- Some routes generate significantly higher profits than others.
- High revenue does not always mean high profitability because operational costs can substantially affect route performance.
- Passenger occupancy is an important factor in route profitability.
- Monthly analysis helps identify periods of higher and lower profitability.
- Geographic visualization helps identify major route-origin clusters.
- Revenue per flight minute provides another way to evaluate route efficiency.
- Loss-making routes can be identified for further operational review.

---

# 📁 Project Structure

```text
SkyRoutes_Airline_Route_Profitability/
│
├── AirlineRoutesData_100000.csv
│
├── SkyRoutesAnalysis.sql
│
├── SkyRoutes_Route_Profit_Dashboard.pbix
│
├── SkyRoutes Airline Route Profitability Dashboard.png
│
└── Route Map & Geographic Analysis.png
