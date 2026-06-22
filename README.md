# 🌤️ Weather WebApp

A modern and responsive weather application built with React that provides real-time weather information using the OpenWeather API. The application displays current weather conditions, forecasts, and dynamic weather-based backgrounds to enhance user experience.

---

# 📑 Table of Contents

- [Demo](#-demo)
- [Getting Started](#-getting-started)
- [Available Scripts](#available-scripts)
- [Project Structure](#-project-structure)
- [Features](#-features)
- [Architecture](#-architecture)
- [Technologies Used](#-technologies-used)
- [Challenges](#-challenges)
- [Roadmap](#-roadmap)
- [Contribution](#-contribution)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

# 🚀 Demo

Run the application locally:

```bash
npm install
npm start
```

Application will be available at:

```bash
http://localhost:3000
```

---

# 🚀 Getting Started

## Prerequisites

Before running the project, make sure you have:

- Node.js
- npm
- An OpenWeather API Key

Create an account at:

https://openweathermap.org/api

---

## Installation

Clone the repository:

```bash
git clone https://github.com/AmitPrajapati9401/Weather-WebApp.git

cd Weather-WebApp
```

Install dependencies:

```bash
npm install
```

---

## Environment Variables

Create a `.env` file in the root directory and add:

```env
REACT_APP_OPENWEATHER_API_KEY=YOUR_API_KEY
```

Replace `YOUR_API_KEY` with your actual OpenWeather API key.

---

# Available Scripts

### Start Development Server

```bash
npm start
```

Runs the app in development mode.

Open:

```bash
http://localhost:3000
```

The page reloads automatically when changes are made.

---

### Run Tests

```bash
npm test
```

Launches the test runner.

---

### Build for Production

```bash
npm run build
```

Builds the application for production and outputs files to the `build` folder.

---

### Eject

```bash
npm run eject
```

> **Warning:** This operation is irreversible.

---

# 📁 Project Structure

```text
Weather-WebApp
│
├── public
│
├── src
│   ├── components
│   ├── pages
│   ├── context
│   ├── assets
│   ├── utils
│   ├── styles
│   ├── App.js
│   └── index.js
│
├── .env
├── package.json
└── README.md
```

---

# ✨ Features

- Real-time weather information
- Search weather by city
- Responsive UI
- Dynamic weather backgrounds
- Current temperature display
- Humidity information
- Wind speed details
- Sunrise and sunset timings
- Forecast support
- Error handling for invalid city names
- OpenWeather API integration

---

# 🏗 Architecture

The application follows a component-based React architecture.

### Frontend

- React
- Context API
- React Hooks

### Styling

- SCSS
- TailwindCSS

### API

- OpenWeather API

### Deployment

- Vercel

---

# 💻 Technologies Used

- React
- JavaScript
- HTML5
- CSS3
- SCSS
- TailwindCSS
- OpenWeather API
- Vercel

---

# ⚠ Challenges

### API Rate Limits

Handling OpenWeather API limitations and minimizing unnecessary API requests.

### Location Search

Implementing efficient city search functionality while maintaining good performance.

### Optimization

Improving page load speed and reducing redundant re-renders.

---

# 🛣 Roadmap

- [ ] Convert project to TypeScript
- [ ] Improve unit testing coverage
- [ ] Add Storybook documentation
- [ ] Weather alerts support
- [ ] Hourly forecast charts
- [ ] Multi-language support
- [ ] Progressive Web App (PWA)
- [ ] Dark/Light theme toggle

---

# 🙌 Contribution

Contributions are welcome.

### Steps to Contribute

Fork the repository.

Create a new branch:

```bash
git checkout -b feature/new-feature
```

Commit your changes:

```bash
git commit -m "Added new feature"
```

Push your branch:

```bash
git push origin feature/new-feature
```

Open a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

Refer to the `LICENSE` file for more details.

---

# 🙏 Acknowledgements

Special thanks to:

- OpenWeather
- React Community
- TailwindCSS
- Vercel

For providing excellent tools and services that make projects like this possible.
