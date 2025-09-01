# 🚌 Bus Route Optimizer for College Students  

## 📌 Project Overview  
This project optimizes **bus routes for college students** by calculating distance, fare, and detailed directions between a **city** and a **college**.  
It uses **OpenRouteService API, Folium for maps, and interactive widgets** for user-friendly selection.  

---

## ✨ Key Features  
- Interactive **city → college route selection**  
- Displays **distance, fare, and step-by-step directions**  
- Generates an **interactive map with markers and routes**  
- Simple fare calculation logic:  
  - Minimum fare: ₹10  
  - ₹1.2 per km above base distance  
- Supports multiple colleges and cities via CSV data  

---

## 📂 Example Dataset Fields  
| Feature      | Description |
|--------------|-------------|
| **Name**     | City or College name |
| **Type**     | City / College |
| **Latitude** | Latitude of the location |
| **Longitude**| Longitude of the location |

---

## 🔎 Methods Summary  
1. Load city and college data from CSV  
2. Select **City** and **College** via dropdown  
3. Fetch optimized **route & directions** using OpenRouteService  
4. Calculate **distance & fare**  
5. Display **step-by-step directions**  
6. Show an **interactive route map with markers**  

---

## 🚀 Future Scope  
- Add **real-time traffic data** for better route optimization  
- Implement **fare discounts/passes** for students  
- Extend to **multiple colleges & bus stops**  
- Deploy as a **web/Android app**  

---

## 📊 Example Output  

```bash
🚏 Kakinada ➡ JNTU Kakinada  
Distance: 5.20 km  
Fare: ₹12.40  

📍 Directions:  
1. Head east on Main Road (500 m)  
2. Turn right towards University Gate (700 m)  
3. Continue straight (4 km)



  

