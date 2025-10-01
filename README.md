# 🌦️ NimbusOne Weather App

A sleek, modern weather dashboard with a conversational AI assistant. NimbusOne provides real-time weather data, dynamic UI themes, and detailed forecasts in an intuitive and visually appealing interface.



## ✨ Features

-   **Real-time Weather Data:** Get current temperature, "feels like" temperature, humidity, wind speed, and chance of rain for any location worldwide.
-   **Dynamic UI & Themes:** The entire app's background and color scheme changes to match the weather and time of day (Day, Night, and Rain themes).
-   **Live Weather Animations:** Instead of static icons, the app displays beautiful animations for:
    -   ☀️ Sun (Clear Day)
    -   🌙 Moon (Clear Night)
    -   ☁️ Clouds (with sun/moon peeking through)
    -   🌧️ Rain
    -   🌨️ Snow
    -   💨 Wind
-   **12-Hour Forecast:** See an hour-by-hour forecast for the next 12 hours, including temperature and precipitation chance.
-   **Air Quality Index (AQI):** A dedicated card shows the real-time AQI, color-coded for easy interpretation from Good to Very Poor.
-   **Intelligent Chatbot Assistant:** The built-in assistant can:
    -   Fetch weather for any city or country (e.g., "weather in london").
    -   Detect your current location (e.g., "humidity in my location").
    -   Answer specific questions about rain, temperature, humidity, and wind.
    -   Provide crucial sea safety advice for fishermen based on wind speed and thunderstorm risk.
-   **Fully Responsive Design:** The layout seamlessly adapts from large desktop monitors to mobile devices.

## 🛠️ Technologies Used

-   **HTML5**
-   **CSS3** (with Grid, Flexbox, and Custom Animations)
-   **Vanilla JavaScript (ES6+)** for all logic, API handling, and DOM manipulation.

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You only need a modern web browser and a code editor.

### Installation & Setup

1.  **Clone the repository** (or download the files):
    ```sh
    git clone [https://github.com/your-username/nimbusone.git](https://github.com/your-username/nimbusone.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd nimbusone
    ```
3.  **Get a Free API Key:**
    This project requires an API key from OpenWeatherMap.
    -   Go to [https://openweathermap.org/appid](https://openweathermap.org/appid) and create a free account.
    -   Generate an API key.

4.  **Configure the API Key:**
    Open the `script.js` file and find the following line at the top:
    ```javascript
    const API_KEY = "YOUR_OPENWEATHERMAP_API_KEY";
    ```
    Replace `"YOUR_OPENWEATHERMAP_API_KEY"` with the actual key you generated.

5.  **Run the App:**
    Simply open the `index.html` file in your web browser. That's it!



