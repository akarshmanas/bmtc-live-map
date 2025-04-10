A real-time map simulation of BMTC buses in Bengaluru using route data, predictive modeling, and modern web technologies. Built to feel like you're watching the city's pulse, even without GPS data.

🚦 Features
🔮 Predictive Bus Movement (no GPS required)

🗺️ Interactive Leaflet Map

🧠 Route-based ETA Simulation

📱 Responsive Design with Mobile Controls

⚡ Real-time UI Updates with WebSockets

🛠️ Built with React + Express + Tailwind + Leaflet

🗃️ Uses Drizzle ORM for lightweight, typesafe data handling

🧱 Tech Stack
Layer	Tech
Frontend	React, TailwindCSS, shadcn/ui, Leaflet
Backend	Express.js (TypeScript), Vite
Real-Time	WebSocket Integration
ORM	Drizzle (Postgres)
Dev Tools	Vite, ESLint, Prettier
📂 Project Structure
bash
Copy
Edit
client/        # Frontend app (React + Leaflet)
 └─ components/
     └─ MapContainer.tsx
     └─ ActiveBuses.tsx
     └─ RouteInfo.tsx
     └─ Sidebar.tsx
     └─ MobileControls.tsx

server/        # Express backend (TypeScript)
 └─ index.ts
 └─ routes.ts
 └─ storage.ts
 └─ vite.ts

public/        # Static files
README.md
🚀 Getting Started (Locally)
bash
Copy
Edit
# 1. Clone the repo
git clone https://github.com/yourusername/bmtc-live-map.git
cd bmtc-live-map

# 2. Install client
cd client
npm install
npm run dev

# 3. In a new terminal: start backend
cd ../server
npm install
npm run dev
🌐 Live Demo
Coming soon – deploy with Vercel/Render/Netlify to let users explore BMTC routes in real time.

📈 Roadmap
 Add ETA-based interpolation for smoother movement

 Integrate Google Maps or OpenRouteService for traffic-aware predictions

 Upload real BMTC route GeoJSON files

 Optional: ML-based delay prediction engine

 Add user-friendly route selection UI

🧠 Why This Project?
Most bus tracking systems rely on GPS—but what if you could simulate real-time movement using data science, schedules, and traffic data? This app explores exactly that. It’s like watching your city breathe, powered by smart code instead of expensive hardware.

