# AnnSarthi (अन्नसारथी) 🌾🍲
**Intelligent Hyper-Local Surplus Food Redistribution & Zero-Waste Operating System**

AnnSarthi is an AI-powered platform designed to eliminate food waste and fight hunger by seamlessly connecting food donors (restaurants, caterers, hotels, institutions) with verified NGOs, shelter homes, and bio-processing centers in real-time.

---

## 🌟 Key Features

- 📸 **AI-Powered Quality & Freshness Assessment**: Automated visual grading using Gemini Multimodal AI to verify food safety, calculate edible shelf-life, and flag allergens.
- ⚡ **Dynamic Greedy Bipartite Matching Algorithm**: Real-time optimal pairing of food donors with closest matching NGOs based on capacity, distance, urgency, and vehicle constraints.
- 🗺️ **Live Geospatial Redistribution Map**: Interactive Leaflet maps tracking active food listings, NGO shelters, collection routes, and food-loss hotspots.
- ❄️ **IoT Cold-Chain & Shelf-Life Telemetry**: Monitoring temperature, humidity, and transit conditions with automated expiry alerts.
- 📊 **Automated ESG & Carbon Offset Reporting**: Instant generation of certified sustainability metrics (Meals Donated, CO2e Avoided, Methane Prevented, Water Saved).
- 📲 **Multi-Channel Access (Offline SMS / Low-Bandwidth Support)**: SMS simulator and offline-first queueing for non-smartphone or rural volunteers.
- ♻️ **Closed-Loop Secondary Redistribution**: If food quality degrades past human consumption safety, automated dispatch diverts surplus to verified biogas/composting/animal feed partners.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 14 (App Router)](https://nextjs.org/)
- **UI & Styling**: [React 18](https://react.dev/), [Tailwind CSS](https://tailwindcss.com/), [Lucide React](https://lucide.dev/)
- **Mapping**: [Leaflet](https://leafletjs.com/) & [React-Leaflet](https://react-leaflet.js.org/)
- **AI Intelligence**: [Google Gemini API](https://ai.google.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)

---

## 🚀 Getting Started

### 1. Prerequisites
- Node.js (v18.x or later)
- npm, yarn, or pnpm

### 2. Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/adarshofficial560-ux/annsarthi.git
cd annsarthi
npm install
```

### 3. Environment Configuration
Create a `.env.local` file in the root directory and add your Gemini API key:
```env
GEMINI_API_KEY=your_gemini_api_key_here
```

### 4. Run Development Server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to explore AnnSarthi.

---

## 📦 Building for Production

```bash
npm run build
npm run start
```

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
