# Weather Search ⛅

Weather Search is a full-stack web application that provides real-time weather forecasts. Built with Angular, Node.js, Express, and MongoDB, it integrates multiple APIs for a seamless and interactive user experience.

> *🔹 Note: Due to academic policies, the full source code is not publicly available. However, this README provides an overview of the project’s features, technologies, and implementation details.*

---

## 🌤️ Overview

- Search by location: Enter an address or use geolocation to fetch real-time weather data.
- Interactive visualizations: Highcharts-powered graphs for daily and hourly forecasts.
- Favorites management: Save locations with persistence via MongoDB Atlas.
- Location autocomplete and maps: Powered by Google Maps API and ipinfo.io.
- Deployed on Google Cloud Platform (GCP).

---

## 🔗 Demo

- **Live Application:** [Weather Search Live](https://csci571asgm3frontend.wl.r.appspot.com/)
- **Video Demo:** 
<video width="100%" height="300rem" controls>
  <source src="assets/demo_compressed.mp4" type="video/mp4">
  Your browser does not support the video tag. [Watch here](assets/demo.mov)
</video>

---

## 🛠️ Tech Stack

### Backend
- Node.js & Express – REST API server with proxy for external API calls.
- MongoDB Atlas – Cloud NoSQL database.
- Tomorrow.io REST API – Fetches real-time weather data.
- Google Geocoding API – Converts user input into geographic coordinates.

### Frontend
- Angular v18 – Component-based UI framework.
- ng-Bootstrap – Responsive UI components.
- Highcharts Angular – Weather visualizations.
- Google Maps API – Autocomplete and map integration.
- ipinfo.io API – Detects user location.

### Cloud & Deployment
- Deployed on Google Cloud Platform (GCP) – Frontend and backend hosted in the cloud.

---

## ✨ Key Features

- Real-time weather search: Fetches and displays weather data instantly.
- Multi-tab weather display:  
  - Day View: 6-day forecast.  
  - Daily Temp. Chart: 15-day temperature trends.  
  - Meteogram: 5-day hourly weather graph.  
- Favorites management: Save locations with MongoDB-backed persistence.
- Social sharing: Tweet weather details directly to X (Twitter).
- Mobile-optimized: Fully responsive for all devices.
- Secure API handling: All external API calls are proxied through the backend.

---

## ⚙️ Challenges & Learnings

- API rate limits & error handling: Optimized API requests for stability.
- Cloud deployment & scaling: Configured backend for efficient request handling.
- Optimized data rendering: Used Angular’s change detection for smooth UI updates.
- Database design: Structured data storage in MongoDB Atlas.

---

## 🚀 Getting Started (For Discussion Purposes)
While the complete source code is not shared publicly, here’s an overview of the development environment:
### Prerequisites
- [Node.js](https://nodejs.org/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- Tomorrow.io API key
- Google Maps Platform API key
- ipinfo.io API token

### Development Environment
- Backend: Node.js with Express.
- Frontend: Angular v18, ng-Bootstrap, and Highcharts Angular.

---

## 📧 Contact

📩 Email: [contact.haozhou@gmail.com](mailto:contact.haozhou@gmail.com)

