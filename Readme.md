# FanHubPlus - Ultimate Fandom & Community Hub

**Project Overview:**
FanHubPlus is a modern web platform for discovering fandom media, character lore, and community events. It brings anime, gaming, comic, and pop-culture fans together to explore multimedia, discover nearby events with interactive maps, view merchandise, and share fan creations. Built using React, Node.js, Express, MongoDB, and Tailwind CSS.

## Key Features

* **Fandom Discovery:** Browse and filter content across anime, gaming, comics, sci-fi, and pop culture
* **Multimedia Hub:** Stream videos, listen to soundtracks and podcasts, and view high-resolution fan art
* **Character Universe:** Explore detailed character wikis, background lore, attributes, and roles
* **Interactive Events & Maps:** Discover fan conventions with Leaflet OpenStreetMap, live distance calculation, and ticket links
* **Merchandise Showcase:** Browse official collectibles, figures, and apparel
* **Fan Submissions:** Community members can submit their own content with admin review workflows
* **Admin Dashboard:** Unified control center with analytics cards to manage content, events, characters, users, and feedback
* **Responsive Design:** Fully responsive layout optimized for mobile, tablet, and desktop

## Main Components

* **EventLocationMap:**
  Interactive OpenStreetMap viewer that plots venue coordinates, shows directions, and calculates the user's distance from the event.
* **MultimediaCenterPage:**
  Tabbed media browser supporting video streaming, audio players with waveforms, and image galleries.
* **AdminAnalyticsCards:**
  Consistent metric cards across admin pages showing total counts, active status, trends, and quick statistics.
* **SignInPromptModal:**
  Polite pop-up that guides guest users to log in when attempting protected community actions.

## Sample Data

* 8 Fandom categories: Anime, Gaming, Comics, Sci-Fi, K-Pop, Cosplay
* 20+ Multimedia items: Videos, audio tracks, and gallery images
* Verified events with GPS map coordinates and official ticket links
* Curated character lore profiles and collectible merchandise items

## Project Structure

```
fanhubplus/
├── Backend/          # Node.js & Express API, MongoDB models, routes, middleware
├── Frontend/         # React application, Vite config, Tailwind styles, components
├── package.json
└── Readme.md
```

## Project Installation Instructions

```bash
# Clone the repository
git clone <repository-url>
cd FanHubPlus

# 1. Setup Backend
cd Backend
npm install
npm run dev          # Starts backend on http://localhost:5000

# 2. Setup Frontend (in a new terminal)
cd Frontend
npm install
npm run dev          # Starts frontend on http://localhost:5173
```

## website Live URL: 
      wwww.abc.com


## Design & UX

* Modern dark fandom theme with violet, cyan, and amber neon accents
* Typography: Inter and Outfit sans-serif fonts for clean readability
* Smooth skeleton loading states for seamless data fetching transitions
* Fully responsive layout with mobile drawer navigation and touch-friendly controls

## Performance & Optimization

* Skeleton loaders to eliminate layout shifts during asynchronous data fetches
* Cloudinary CDN integration for optimized image and media delivery
* Component code-splitting powered by Vite
* Indexed MongoDB queries for fast data retrieval

## Security & Data Handling

* JWT (JSON Web Token) authentication with protected API endpoints
* Role-based access control separating regular users and administrators
* Input validation, password hashing with bcrypt, and sanitization
* Secure media uploads handled via Multer and Cloudinary

## Limitations & Future Plans

* Direct in-app merchandise checkout and payment gateway integration
* Real-time community discussion rooms and live event chat
* Push notifications for upcoming fandom conventions and ticket releases
* Native mobile application support (React Native)

**Team:** SFC REBELS
**Competition:** TechWiz 07

**Developed with ❤️ by SFC REBELS**
