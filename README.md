# Airbnb_Booking_Trends_19 CaseCraft Analytics Project Sprint Project 19

## 🏡 Overview  
This project analyzes Airbnb booking trends using synthetic geospatial, pricing, and behavioral data. It blends clustering, bubble maps, and regression modeling to uncover booking hotspots and predict listing prices.

## 🎯 Objective  
To identify spatial booking patterns, analyze lead time dynamics, and build a price prediction model using listing features.

## 📍 Dataset & Features  
- Listings: 500 synthetic entries  
- Features:  
  - Latitude, Longitude  
  - Price (₹), Lead Time (days)  
  - Room Type: Entire home, Private room, Shared room  
  - Reviews count  
- Derived: price tiers, booking clusters

## 📊 Visual Explorations  
- **Bubble Map**: Booking hotspots in Mumbai (size = price, color = lead time)  
- **Histogram**: Price distribution by room type  
- **Boxplot**: Lead time variation across room types  
- **Heatmap**: Feature correlations (price, lead time, reviews)  
- **Scatterplot**: Reviews vs Price with regression line  
- **Scatterplot**: Lead Time vs Price by room type

## 🔍 Clustering & Modeling  
- **Clustering**: K-Means reveals 4 pricing zones across Mumbai  
- **Regression Model**:  
  - Input: room type, reviews, lead time  
  - Target: price  
  - Model: Random Forest Regressor  
  - Performance: MAE ≈ **₹3,023**

## 🧠 Key Insights  
1. **Hotspot Zones**: High-price listings cluster near Bandra and Colaba  
2. **Lead Time Dynamics**: Inverse correlation with price for Entire homes  
3. **Room Type Impact**: Entire homes command higher prices and shorter lead times  
4. **Review Influence**: Positive correlation with price across room types  
5. **Model Utility**: Predicts listing price with strong accuracy using behavioral features

## ✅ Final Conclusion  
Airbnb booking trends reveal spatial and behavioral segmentation. Hosts can optimize pricing and availability using lead time, location clusters, and review volume. This framework supports dynamic pricing, traveler targeting, and strategic listing management.