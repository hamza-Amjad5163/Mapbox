![image](https://github.com/user-attachments/assets/f5a4ae85-5b7e-41dc-8b10-21a44047d6e7)
![Untitled design (3)](https://github.com/user-attachments/assets/e9e08f99-2546-467a-b03e-325ddc8857ea)


# Mapbox Integration in React
## 🚀 Project Overview
This project demonstrates how to seamlessly integrate **Mapbox** into a React application for building dynamic, interactive, and responsive maps. It supports customizable markers, user location tracking, zoom controls, and more, offering a powerful mapping experience.

---

## 🎯 Features

- 🗺️ **Interactive Maps:** Zoom, pan, and dynamic map rendering.
- 📍 **Custom Markers:** Add markers to pinpoint locations on the map.
- 📡 **User Location Tracking:** Real-time geolocation features.
- ⚡ **Fast & Responsive:** Smooth performance on all screen sizes.

---

## 🛠️ Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/mapbox-react-app.git
cd mapbox-react-app
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Get a Mapbox Access Token
- Sign up or log in to [Mapbox](https://www.mapbox.com/).
- Go to **Account Settings** and generate an access token.

### 4. Set Environment Variables
Create a `.env` file in the root directory and add your Mapbox token:

```
REACT_APP_MAPBOX_TOKEN=your_access_token_here
```

### 5. Start the Application
```bash
npm start
```
The app will run at [http://localhost:3000](http://localhost:3000).

---

## 🧑‍💻 Usage

1. Open the app in your browser.
2. Interact with the map to zoom, pan, and see markers.
3. Customize the map style and add features as needed.

---

## 🛠️ Technologies Used

- **React** for the front-end framework
- **Mapbox GL JS** for map rendering
- **Bootstrap** for responsive design (optional)


## 🌍 Mapbox Configuration
To customize the map style or features, explore the [Mapbox Studio](https://studio.mapbox.com/) and apply changes in the code.

Example of adding markers:

```javascript
import mapboxgl from 'mapbox-gl';

mapboxgl.accessToken = process.env.REACT_APP_MAPBOX_TOKEN;
const map = new mapboxgl.Map({
  container: 'map-container',
  style: 'mapbox://styles/mapbox/streets-v11',
  center: [-74.5, 40],
  zoom: 9
});

new mapboxgl.Marker()
  .setLngLat([-74.5, 40])
  .addTo(map);
```

---

## 🤝 Contributions
Contributions are welcome! Feel free to fork the repository and submit pull requests.
