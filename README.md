# 🌦️ Weather API Dashboard – Power BI

A real-time, interactive dashboard built using **Power BI**, powered by live **Weather API** data. This project provides intuitive visuals for monitoring current weather, air quality, and 7-day forecasts across major Indian cities.

---

## 📌 Features

- 🌡️ **Live Weather Metrics** – Temperature, humidity, wind speed, UV index, and precipitation
- 📅 **7-Day Forecast** – Daily high/low temperatures with visual trends
- 🌅 **Sunrise & Sunset Times** – City-wise visualization
- 💨 **Air Quality Index** – Real-time AQI data including PM2.5, NO₂, CO, O₃, and more
- 🧭 **Clean Visuals & Interactivity** – Filters, cards, and graphs for easy navigation

---

## 🛠️ Tools & Technologies

| Tool         | Purpose                                 |
|--------------|-----------------------------------------|
| Power BI     | Data visualization and dashboard design |
| Power Query  | API integration and data transformation |
| DAX          | Calculated measures and data modeling   |
| WeatherAPI   | Real-time weather data source           |

---

## 📈 Sample Dashboard Layout

> *(Add actual screenshots here if uploading to GitHub)*

- **Weather Cards** showing temperature, humidity, wind speed, and condition icons  
- **Line Chart** of daily forecasted temperature  
- **Bar Chart or Donut Chart** for AQI pollutants  
- **Sunrise/Sunset timeline** for selected cities

---

## 🧪 How It Works

1. **API Integration:**  
   The dashboard pulls real-time weather data using the [WeatherAPI](https://www.weatherapi.com/), transformed via **Power Query (M)**.

2. **Data Modeling:**  
   Preprocessed and reshaped JSON data is structured into a star schema using DAX.

3. **Dynamic Refresh:**  
   Each refresh fetches the most updated weather and AQI data.

4. **User Interaction:**  
   Users can filter by city, date, or specific weather parameters for targeted insights.

---

## 🚀 How to Use

> **Requirements:**  
> - Power BI Desktop  
> - API key from [WeatherAPI](https://www.weatherapi.com/)

### Steps:
1. Clone this repository or download the `.pbix` file.
2. Open it in **Power BI Desktop**.
3. Go to `Transform Data` → replace the API key with your own.
4. Click `Refresh` to load live data.
5. Explore and customize the dashboard!

---

## 🧠 What I Learned

- Integrating and parsing JSON API data in Power BI  
- Real-time dashboard design for non-business use cases  
- Enhancing UX with clean visuals and meaningful metrics  
- AQI calculation and pollutant representation techniques

---

## 📌 Future Improvements

- Add more cities dynamically  
- Use OpenWeatherMap or AQICN APIs as alternatives  
- Embed the dashboard on a web app using Power BI service  
- Enable hourly forecast view

---

## 🔗 API Reference

- [WeatherAPI Documentation](https://www.weatherapi.com/docs/)
- Alternative: [OpenWeatherMap](https://openweathermap.org/api)

---

## 🤝 Connect With Me

Feel free to share feedback or ideas for collaboration!

- 🔗 [LinkedIn](https://www.linkedin.com/abhishaw020/) *(Insert your profile link)*
- 📬 [Email](mailto:abhishaw020@gmail.com)

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---
