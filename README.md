# WeatherApp-React
# 🌦️ Weather App — React.js & Material UI

A modern, responsive weather application built with **React.js and Material UI** that allows users to check real-time weather information for cities around the world.

### 🚀 Live Demo

🔗 **Live Website:** https://weather-app-react-och8nx073-manish-yadav1.vercel.app/

🔗 **GitHub Repository:** https://github.com/manishyadav9694/WeatherApp-React

### 📸 Screenshot

![Weather App Screenshot](screenshot.png)

### ✨ Features

* 🔍 **City Search:** Search for weather information for any supported city.
* 🌡️ **Real-Time Weather:** View current temperature and weather conditions.
* 💧 **Humidity:** Check the current humidity level.
* 🌤️ **Feels Like:** View the feels-like temperature.
* ⚠️ **Error Handling:** Displays appropriate errors for invalid city names or failed API requests.
* 🎨 **Modern UI:** Clean interface built using Material UI components.
* 📱 **Responsive Design:** Works across desktop, tablet, and mobile devices.

### 🛠️ Tech Stack

| Technology        | Purpose                           |
| ----------------- | --------------------------------- |
| React.js          | Building the user interface       |
| Vite              | Development server and build tool |
| Material UI (MUI) | UI components and design          |
| CSS3              | Styling and responsive layout     |
| OpenWeather API   | Fetching weather data             |
| Vercel            | Deployment and hosting            |

### 📁 Project Structure

```text
WeatherApp-React/
├── public/
│   └── screenshot.png
├── src/
│   ├── components/
│   ├── App.jsx
│   ├── main.jsx
│   └── App.css
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

*Note: Update the project structure above to match your actual files and folders.*

### ⚙️ Installation & Setup

**1. Clone the repository**

```bash
git clone https://github.com/manishyadav9694/WeatherApp-React.git
```

**2. Navigate to the project directory**

```bash
cd WeatherApp-React
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm run dev
```

Open the local URL displayed in your terminal to view the application.

### 🔑 API Configuration

This project uses the OpenWeather API to retrieve weather information.

1. Create an account on OpenWeather and obtain an API key.
2. Configure the API key using the environment variable expected by your application.
3. If using Vite, store the variable in a `.env` file and access it using `import.meta.env`.

Example:

```env
VITE_WEATHER_API_KEY=your_api_key_here
```

**Important:** Never upload your actual API key or other secrets to GitHub. Add `.env` to `.gitignore` and use the appropriate environment variable settings when deploying to Vercel.

### 🌐 Deployment

This application can be deployed using Vercel.

1. Import your GitHub repository into Vercel.
2. Configure the required environment variables.
3. Deploy the application.
4. Add your live website URL to the Live Demo section above.

### 👨‍💻 Author

**Manish Yadav**
B.Tech Computer Science & Engineering Student

* 💻 GitHub: [manishyadav9694](https://github.com/manishyadav9694)
* 💼 LinkedIn: [Manish Yadav](https://www.linkedin.com/in/manish-yadav/)

---

⭐ If you find this project useful, consider giving the repository a star!
