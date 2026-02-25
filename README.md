# 🌤 Weather API Fetch – Weather-Based Quote Generator

Weather API Fetch is a weather-powered application that displays dynamic quotes based on real-time weather conditions.

If it's raining 🌧 → The app shows reflective or sad quotes.  
If it's sunny ☀ → The app shows happy, optimistic, and motivational quotes.

This project demonstrates API integration, conditional logic, and dynamic content rendering.

---

## 🚀 Features

- 🌍 Real-time Weather API integration
- 🌧 Displays sad/reflective quotes during rainy weather
- ☀ Displays happy/optimistic quotes during sunny weather
- 🔄 Automatic quote switching based on weather condition
- 🧠 Clean and scalable logic structure
- ⚡ Lightweight and easy to deploy

---

## 🛠 Tech Stack (Example)

- C# / .NET (or JavaScript / React depending on your implementation)
- REST Weather API (e.g., OpenWeatherMap)
- JSON parsing
- HTTP Client requests

---

## 📦 How It Works

1. The app fetches real-time weather data from a Weather API.
2. It checks the current weather condition:
   - If `Rain` → Select random sad quote.
   - If `Clear` or `Sunny` → Select random happy quote.
3. The selected quote is rendered dynamically on the UI.

---

## 🧩 Sample Logic (Pseudo-code)

```csharp
if (weatherCondition == "Rain")
{
    DisplayRandomQuote(sadQuotes);
}
else if (weatherCondition == "Clear")
{
    DisplayRandomQuote(happyQuotes);
}
