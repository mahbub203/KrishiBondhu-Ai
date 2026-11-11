# 🌾 KrishiBondhu AI (কৃষিবন্ধু এআই)
### *Smart Agriculture & AI-Powered Agricultural Assistance for Bangladesh*

[![IUBAT Technocrats V.2 Award](https://img.shields.io/badge/Award-1st%20Runner--Up%20%F0%9F%8F%86-FFD700?style=for-the-badge&logo=trophy&logoColor=black)](https://github.com/mahbub203/KrishiBondhu-Ai)
[![Competition](https://img.shields.io/badge/Competition-IUBAT%20National%20Innovation%20Competition%202024%20(Technocrats%20V.2)-008080?style=for-the-badge)](https://github.com/mahbub203/KrishiBondhu-Ai)
[![Course](https://img.shields.io/badge/Project-Web%20Engineering%20Capstone-blue?style=for-the-badge)](https://github.com/mahbub203/KrishiBondhu-Ai)

[![Next.js 15](https://img.shields.io/badge/Next.js-15.3.3-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18.3.1-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Firebase](https://img.shields.io/badge/Firebase-11.9-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Google Genkit](https://img.shields.io/badge/Genkit_AI-1.20-4285F4?style=flat-square&logo=google&logoColor=white)](https://firebase.google.com/docs/genkit)
[![Gemini](https://img.shields.io/badge/AI_Model-Google_Gemini-8E75C2?style=flat-square&logo=googlegemini&logoColor=white)](https://deepmind.google/technologies/gemini/)

---

<p align="center">
  <img src="public/icon.png" alt="KrishiBondhu AI Logo" width="220" style="border-radius: 20px; box-shadow: 0 4px 20px rgba(0,0,0,0.15);" />
</p>

<p align="center">
  <strong>Empowering rural farmers with localized AI intelligence, voice guidance, and real-time agricultural advisories in native Bangla.</strong>
</p>

---

## 🏆 Accolades & Recognition

- **🥈 1st Runner-Up**: IUBAT National Innovation Competition 2024 *(Technocrats V.2)*
- **Academic Milestone**: Web Engineering Project Capstone

---

## 📌 Problem Statement

In Bangladesh, agriculture supports over 40% of the labor force. However, smallholder farmers face critical bottlenecks:
1. **Pest & Crop Disease Outbreaks**: Delayed diagnosis leads to devastating harvest losses of 20–30%.
2. **Language & Literacy Barriers**: Traditional technical documentation and apps are inaccessible to farmers who cannot read complex technical English.
3. **Climate Vulnerability**: Unpredicted heavy downpours, flash floods, and cold waves catch farmers unprepared.
4. **Middleman Exploitation**: Inadequate access to daily mandi/wholesale prices and government subsidy schemes reduces farmer profit margins.

**KrishiBondhu AI** solves these challenges by combining **Google Gemini via Genkit**, **Firebase Firestore**, and a **Bangla-first conversational UI** into an accessible, responsive web application.

---

## ✨ Key Features

### 🩺 1. AI Crop Doctor (এআই শস্য ডাক্তার)
- Upload or capture photos of infected plant leaves and stems.
- Multimodal AI vision analysis powered by Google Gemini to identify pests, fungus, bacterial blight, and nutritional deficiencies.
- Provides immediate localized remedies (organic & chemical options) and prevention steps in fluent Bangla.

### 🎙️ 2. Mati AI Voice Assistant (মাটি এআই ভয়েস সহকারী)
- Hands-free natural Bangla speech-to-intent interface designed for low-literacy users.
- Farmers can speak directly into the app about soil issues, seed varieties, fertilizer ratios, or crop problems.

### 🌦️ 3. Hyper-Local Weather Advisor & Disaster Alerts (আবহাওয়া ও সতর্কবার্তা)
- Real-time district and Upazila weather forecast.
- Automated severe weather advisories (cyclone, heavy rain, drought alerts) with concrete action checklists for crop preservation.

### 🌱 4. Smart Crop Planning (আমার ফসল)
- Seasonal crop recommendation engine based on current month, soil category, and agro-ecological zones of Bangladesh.
- Step-by-step planting, irrigation, and harvesting lifecycle tracking.

### 📊 5. Daily Market Prices & Government Schemes (বাজার দর ও সরকারি সুবিধা)
- Up-to-date wholesale and retail market prices for key vegetables, rice varieties, and fruits.
- Search and eligibility guide for agricultural subsidies, grants, fertilizer quotas, and government stimulus schemes.

### 👨‍💼 6. Krishi Officer Directory (কৃষি কর্মকর্তা অনুসন্ধান)
- Directory of Department of Agricultural Extension (DAE) officers categorized by division, district, and upazila.
- Direct contact access to certified local extension workers.

### 👥 7. Farmer Community Network (কৃষক সম্প্রদায়)
- Community board for farmers to share experiences, upload crop photos, discuss solutions, and learn from neighboring farming communities.

### 🌐 8. Bilingual Bangla & English Support (দ্বিভাষিক সমর্থন)
- Seamless real-time language toggling between Bengali (`bn`) and English (`en`) across every screen and flow.

---

## 🛠️ Technology Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend Framework** | [Next.js 15.3.3](https://nextjs.org/) (App Router, Turbopack) |
| **UI Library** | [React 18.3.1](https://react.dev/), [Tailwind CSS 3.4](https://tailwindcss.com/) |
| **Components & Icons** | [Radix UI](https://www.radix-ui.com/), [shadcn/ui](https://ui.shadcn.com/), [Lucide React](https://lucide.dev/) |
| **Charts & Visuals** | [Recharts 2.15](https://recharts.org/) |
| **Generative AI** | [Google Genkit 1.20](https://firebase.google.com/docs/genkit), [Google Gemini API](https://deepmind.google/technologies/gemini/) |
| **Backend & Cloud** | [Firebase 11.9](https://firebase.google.com/) (Firestore, Auth, App Hosting) |
| **Validation & State** | [Zod 3.24](https://zod.dev/), [React Hook Form 7.54](https://react-hook-form.com/) |
| **Type Safety** | [TypeScript 5](https://www.typescriptlang.org/) |

---

## 📂 Project Architecture

```plaintext
KrishiBondhu-Ai/
├── .idx/                      # Project IDX development environment configuration
├── docs/                      # Architectural blueprints & backend specifications
│   ├── backend.json
│   └── blueprint.md
├── public/                    # Static assets, hero video & brand icon
│   ├── icon.png
│   └── hero-video.mp4
├── src/
│   ├── ai/                    # Genkit AI Flows & Google Gemini integrations
│   │   ├── flows/
│   │   │   ├── ai-crop-doctor-analysis.ts     # Multimodal plant diagnosis flow
│   │   │   ├── critical-weather-alert-flow.ts # Disaster alerting flow
│   │   │   ├── crop-guidance-flow.ts          # Step-by-step planting advisor
│   │   │   ├── farming-news-flow.ts           # Agricultural news curation
│   │   │   ├── government-scheme-finder.ts    # Subsidies & incentives finder
│   │   │   ├── krishi-officer-finder.ts       # DAE officer locator
│   │   │   ├── market-price-finder.ts         # Wholesale & retail price tracking
│   │   │   ├── mati-ai-voice-assistance.ts    # Voice-driven Bangla assistant
│   │   │   ├── optimal-crop-suggestion.ts     # Seasonal crop recommendation
│   │   │   ├── universal-search-flow.ts       # Global agro-query search
│   │   │   └── weather-advisor-flow.ts        # Weather analysis & recommendations
│   │   └── genkit.ts          # Genkit initialization
│   ├── app/                   # Next.js 15 App Router pages & layouts
│   │   ├── about/             # Team & project overview
│   │   ├── community/         # Peer-to-peer discussion forum
│   │   ├── crop-doctor/       # AI disease detection interface
│   │   ├── find-officer/      # Extension officer directory
│   │   ├── market-info/       # Market prices & gov schemes
│   │   ├── my-crops/          # Crop management & scheduler
│   │   ├── voice-assistant/   # Mati AI voice interaction UI
│   │   ├── weather/           # Weather radar & forecasting
│   │   ├── layout.tsx         # Root layout with sidebar navigation
│   │   └── page.tsx           # Main dashboard overview
│   ├── components/            # Reusable UI & presentation components
│   │   ├── ui/                # Base design-system primitives (Radix UI)
│   │   └── app-header.tsx     # Dynamic navigation header
│   ├── context/               # Global state (Language, Geolocation)
│   ├── firebase/              # Firebase client SDK initialization & Firestore hooks
│   ├── hooks/                 # Custom React hooks (geolocation, media queries)
│   └── lib/                   # Localization dictionaries (i18n), weather APIs & utility functions
├── apphosting.yaml            # Firebase App Hosting deployment configuration
├── firestore.rules            # Security rules for Cloud Firestore
├── tailwind.config.ts         # Custom Tailwind theme & color tokens
└── tsconfig.json              # TypeScript compilation configuration
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v20 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Firebase Account](https://firebase.google.com/)
- [Google AI Studio API Key](https://aistudio.google.com/) for Gemini

### 1. Clone the Repository

```bash
git clone https://github.com/mahbub203/KrishiBondhu-Ai.git
cd KrishiBondhu-Ai
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env.local` file in the root directory:

```env
# Google Gemini / Genkit API Key
GEMINI_API_KEY=your_gemini_api_key_here

# Firebase Configuration
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

### 4. Run the Development Server

```bash
npm run dev
```

Open [http://localhost:9002](http://localhost:9002) in your browser to view the application.

### 5. Run Genkit AI Developer UI (Optional)

To test and inspect Genkit AI flows locally:

```bash
npm run genkit:dev
```

---

## 👨‍💻 Author

**Abdullah Al Jubair Prince**  
- GitHub: [@mahbub203](https://github.com/mahbub203)
- LinkedIn: [linkedin.com/in/aajubairprincee](https://www.linkedin.com/in/aajubairprincee/)
- Facebook: [facebook.com/jubair.prince009](https://www.facebook.com/jubair.prince009/)

---

## 📄 License

This project was developed for the **Web Engineering Course** and **IUBAT National Innovation Competition 2024 (Technocrats V.2)**.  
All rights reserved © 2024-2026.
