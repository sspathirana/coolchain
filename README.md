
# Cold Chain GPS Dashboard

This is a real-time dashboard for tracking multiple cold chain devices using Firebase and Google Maps.

## 🌍 Features

- Live location display for multiple devices
- Polyline trails showing historical GPS movement
- InfoWindows with temperature and timestamp
- Toggle trail visibility per device
- Date & time filter
- CSV Export of all visible data
- Responsive mobile-friendly design

## 🚀 Deployment on GitHub Pages

1. Create a GitHub repository (e.g., `cold-chain-gps`)
2. Upload `index.html` and `README.md`
3. Go to **Settings → Pages**
4. Set **Source** to `main` branch, root (`/`) directory
5. Visit your site at:
   ```
   https://your-username.github.io/cold-chain-gps/
   ```

## 🔧 Firebase Setup

- Create a [Firebase Realtime Database](https://console.firebase.google.com/)
- Replace `databaseURL` in `index.html` with your own
- Your data structure should look like:

```
/gps/device1/20240630120000
  ├─ latitude: 6.927
  ├─ longitude: 79.861
  ├─ temperature: 28.5
  ├─ timestamp: "2024-06-30T12:00:00"
```

## 🔐 Google Maps API

- Get a free API key from [Google Cloud Console](https://console.cloud.google.com/)
- Enable the **Maps JavaScript API**
- Replace the `key=...` in the Google Maps script URL

## 📜 License

Free to use and modify for academic or personal projects.
