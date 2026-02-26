🌍 Geospatial AI — GeoGemma Powered Precision Agriculture

Developer: Aman Kumar

Geospatial AI is an advanced precision agriculture platform that transforms satellite Earth Observation data into actionable farming insights. It integrates satellite imagery, weather intelligence, and multi-modal AI to monitor crop health, detect anomalies, and generate localized advisory recommendations.

The platform is powered by GeoGemma, a Spatial Foundation Model designed to automate geospatial analysis and reduce GIS task completion time by ~74%.

🚀 Features

🛰 Satellite-based crop monitoring (Sentinel-2)

🌿 NDVI & LAI vegetation index computation

🌦 Real-time weather integration

📸 AI-based crop disease detection

🗺 Interactive geospatial map visualization

📊 Field-level anomaly detection

🧠 AI-generated farming advisory

📈 Market insights and recommendations

⚙️ How It Works
1️⃣ Data Ingestion

Sentinel-2 multispectral satellite imagery

NDVI and LAI vegetation analysis

Real-time weather data integration

2️⃣ GeoGemma AI Engine

Geospatial Location Embedding (GLE)

Vision-Language Model alignment

Gemini AI for spatial analysis and advisory

3️⃣ Output & Interface

Image-based crop diagnosis

Interactive maps

Localized advisory reports

🛠 Tech Stack
Category	Technology
Frontend	React, Vite, Tailwind CSS
Backend & Auth	Supabase, Google OAuth
AI Models	Gemini API, GeoGemma SFM
Maps & GIS	Leaflet, React-Leaflet
State Management	React Hook Form, Zod
Deployment	Vercel
📁 Project Structure
project-root/
│
├── README.md
├── src/
│   ├── geospatial/
│   ├── pages/
│   ├── components/ui/
│   └── App.jsx
│
├── supabase/
├── package.json
└── .env
⚡ Getting Started
Prerequisites

Node.js installed

Supabase account

Gemini API key

Weather API key

Google OAuth credentials

Environment Setup

Create .env file:

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_key
VITE_GEMINI_API_KEY=your_gemini_key
VITE_WEATHER_API_KEY=your_weather_key
VITE_GOOGLE_CLIENT_ID=your_google_id
VITE_GOOGLE_CLIENT_SECRET=your_google_secret
Install Dependencies
npm install
Run Project
npm run dev

App runs at:

http://localhost:5173
🎯 Use Cases

Precision agriculture monitoring

Crop disease detection

Smart farming decision support

Remote field analysis

Agricultural research

👨‍💻 Author

Aman Kumar
B.Tech — Ramgarh Engineering College
AI • Geospatial Computing • Precision Agriculture
