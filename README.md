# Delhi-NCR-Ride-Booking-Analytics-Dashboard-Power-BI
Developed an interactive Power BI dashboard to analyze ride-booking performance across Delhi NCR, with focus on demand, booking value, cancellation behavior, ride completion, and operational efficiency. The dashboard enables users to dynamically filter performance by month, vehicle type, &amp; cancellation/incomplete-ride reasons &amp; identify bottlenecks
# 🚖 Delhi NCR Ride Booking Analytics Dashboard | Power BI

## 📊 Project Overview

This project presents an interactive **Power BI dashboard for analyzing ride-booking data across Delhi NCR**.

The dashboard was designed to provide insights into **booking trends, vehicle-wise demand, booking value, ride performance, customer/driver cancellations, incomplete rides, and operational efficiency**.

The objective is to transform raw ride-level data into an interactive business intelligence solution that can help identify demand patterns, operational bottlenecks, and opportunities for improving ride-booking performance.

---

## 🎯 Business Objective

The key objectives of this project are to:

- Analyze ride bookings across different vehicle categories
- Understand vehicle-wise booking volume and booking value
- Identify major reasons for customer and driver cancellations
- Analyze incomplete rides and their underlying reasons
- Compare operational metrics such as VTAT and CTAT across vehicle types
- Understand ride distance and booking-value patterns
- Provide actionable insights for fleet and operational planning

---

## 🗂️ Dataset

The dataset contains booking-level ride information for Delhi NCR.

### Key Data Attributes

- Date & Time
- Booking ID
- Booking Status
- Customer ID
- Vehicle Type
- Pickup Location
- Drop Location
- Average VTAT
- Average CTAT
- Customer Cancellation
- Customer Cancellation Reason
- Driver Cancellation
- Driver Cancellation Reason
- Incomplete Rides
- Incomplete Ride Reason
- Booking Value
- Ride Distance
- Driver Rating
- Customer Rating
- Payment Method

---

## 📈 Dashboard Features

The Power BI dashboard provides an interactive view of ride-booking performance.

### 1. Vehicle Performance Analysis

Analyzes **VTAT and CTAT across different vehicle types** to compare operational performance.

Vehicle categories include:

- Auto
- Go Mini
- Go Sedan
- Bike
- Premier Sedan
- eBike
- Uber XL

### 2. Booking Volume Analysis

Shows the distribution of bookings across vehicle categories to identify the most frequently used ride types.

### 3. Booking Value Analysis

Analyzes the contribution of different vehicle categories to overall booking value.

This allows comparison between:

> **Ride Volume vs. Value Contribution**

### 4. Cancellation Analysis

Analyzes customer cancellation reasons to identify potential operational and service-related issues.

Examples include:

- Driver is not moving towards pickup location
- Driver asked to cancel
- Change of plans
- AC is not working
- Wrong Address

### 5. Interactive Filtering

The dashboard allows users to dynamically filter the analysis using:

- Month
- Vehicle Type
- Customer Cancellation Reason
- Driver Cancellation Reason
- Incomplete Ride Reason

---

## 🔍 Key Insights

Based on the dashboard analysis:

- **Auto** represents one of the strongest vehicle categories in terms of booking activity and booking value.
- **Go Mini and Go Sedan** are also significant contributors to overall ride demand.
- Vehicle categories show different VTAT and CTAT patterns, indicating differences in operational performance.
- Cancellation analysis highlights driver-related issues as an important area for operational improvement.
- Incomplete rides require separate monitoring because their causes differ from standard cancellations.
- Comparing booking volume with booking value provides a better understanding of vehicle-category performance than looking at ride count alone.

---

## 💡 Business Recommendations

### 1. Optimize Fleet Allocation

Use vehicle-wise booking trends to allocate drivers and vehicles according to demand.

### 2. Reduce Driver-Related Cancellations

Investigate recurring driver cancellation reasons such as:

- Driver not moving toward pickup
- Driver asking customer to cancel
- Personal/car-related issues

Reducing these issues can improve customer experience and booking completion.

### 3. Improve Pickup Efficiency

Monitor VTAT across vehicle categories and locations to identify areas with longer pickup times.

### 4. Monitor Incomplete Rides

Track incomplete ride reasons such as vehicle breakdown and customer-related issues separately from cancellations.

### 5. Evaluate Vehicle Categories Using Multiple KPIs

Vehicle performance should be evaluated using a combination of:

- Booking volume
- Booking value
- VTAT
- CTAT
- Ride distance
- Cancellation rate
- Customer ratings

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard development & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Measures & analytical calculations |
| **Excel/CSV** | Source data |
| **Data Visualization** | Business insight generation |

---

## 📊 Dashboard Preview

![Delhi NCR Ride Booking Dashboard](screenshots/dashboard.png)

---

## 📌 Key KPIs

The dashboard focuses on key operational and business metrics such as:

- Total Bookings
- Booking Value
- Vehicle-wise Booking Volume
- Vehicle-wise Booking Value
- VTAT
- CTAT
- Customer Cancellations
- Driver Cancellations
- Incomplete Rides
- Ride Distance
- Driver & Customer Ratings

---

## 🎨 Dashboard Filters

The dashboard provides interactive slicers for:

**Month | Vehicle Type | Customer Cancellation Reason | Driver Cancellation Reason | Incomplete Ride Reason**

These filters allow users to drill down from an overall view to specific vehicle categories and operational issues.
