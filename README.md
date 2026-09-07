# Weather

A responsive weather dashboard built with Vite and vanilla JavaScript.

## Features

- Live current conditions and five-day forecasts
- Hourly weather outlook
- City search
- Precise browser location support
- Celsius/Fahrenheit switching
- Sunrise and sunset details
- Offline fallback forecast

## Run Locally

Open PowerShell in this folder and run:

```powershell
npm install
npm run dev
```

Open the local URL shown by Vite, usually:

```text
http://127.0.0.1:5173/
```

If that port is already in use, Vite will select another available port and display it in the terminal.

## Production Build

Create a production build with:

```powershell
npm run build
```

Preview the production build locally with:

```powershell
npm run preview
```

## Location Access

Click the location button in the app and allow browser location access when prompted. Evans Weather requests a fresh, high-accuracy position and reverse-geocodes it to identify the nearby city.

Location access works on `localhost` and secure HTTPS sites. Browsers may block precise location on unsecured external HTTP pages.

## Data Sources

Weather and geocoding data are provided by [Open-Meteo](https://open-meteo.com/). No API key is required.
