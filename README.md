# Echonym — Anonymous Social Media

> **Say what you actually think. No name. No judgment. No identity.**

Echonym is a privacy-first anonymous social platform where anyone — introverts, extroverts, everyone in between — can freely express themselves through text, images, voice, and polls without the pressure of identity.

[<img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="50">](https://play.google.com/store/apps/details?id=app.echonym)

---

## ✨ Features

### 🏠 Home Feed
- Anonymous posts from groups and interests you join
- Facebook-style emoji reactions, comments, saves, and shares
- Real-time updates powered by Firebase Firestore

### 🔍 Explore Page
- **Trending Worldwide** — ranked by engagement across the platform
- **Trending Nearby** — content ranked by user approximate location
- Discover fresh voices entirely anonymously

### 🎙️ Voice Posts with Live Audio Filters
The standout feature of Echonym. Users can record voice posts with real-time audio filters applied directly to the audio — not just playback effects:
- 🤖 Robot
- 🎈 Helium
- 🔊 Deep
- 🔁 Echo

Full-screen immersive voice player for feed posts. Compact player for group voice messages.

### ➕ Post Types
- Text posts
- Image posts
- Voice posts with audio filters
- Polls

### 👥 Groups
- Interest-based communities (e.g. Mental Health, Gaming, Tech)
- Location-based communities (e.g. Karachi, Islamabad)
- Text, image, and voice messaging within groups

### 👤 Profile
- View your own anonymous posts
- Saved posts collection
- Settings — filter preferences, interests, and privacy controls

---

## 🚫 What Echonym Deliberately Excludes
| Feature | Why It's Excluded |
|---|---|
| Direct Messages | Prevents identity-based conversations and harassment |
| Followers / Following | Removes social pressure and clout dynamics |
| Reposts / Retweets | Keeps content organic and prevents virality loops |
| Real Name or Photo | Full anonymity — always |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | Flutter (Dart) |
| State Management | Riverpod |
| Navigation | GoRouter |
| Authentication | Firebase Auth (Anonymous) |
| Database | Firebase Firestore |
| Media Storage | Firebase Storage |
| Push Notifications | Firebase Cloud Messaging (FCM) |
| Backend Logic | Firebase Cloud Functions (TypeScript) |
| Real-Time | Firebase Realtime Database |

---

## 📱 Platform
- **Android** — Live on Google Play Store
- Minimum SDK: Android 6.0 (API 23)

---

## 📂 Project Structure

```
lib/
├── main.dart               # App entry point and initialization
├── app_router.dart         # GoRouter navigation and auth guards
├── app_theme.dart          # Brand colors and theme definitions
├── controllers/            # Page controllers and state notifiers
├── models/                 # Data models (Post, Group, User, Comment)
├── providers/              # Riverpod providers
├── repositories/           # Data layer — Firestore queries and caching
├── services/               # Firebase services (Auth, FCM, Storage)
├── screens/                # App screens (Feed, Explore, Groups, Profile)
└── widgets/                # Reusable UI components and voice player
```

---

## 🎨 Design Philosophy

Clean, modern, and minimal — but bold. Inspired by Instagram's polish, Reddit's community structure, and TikTok's content discovery, but built entirely around anonymity. The UI never exposes identity at any point in the user journey.

---

## 🔐 Privacy Architecture

- No real name, photo, or personal identifier is ever stored
- Anonymous Firebase Auth sessions
- Location data used only for approximate content discovery — never stored precisely
- No DMs eliminates the primary vector for identity exposure and harassment

---

## 📲 Download

Available on Google Play Store:
**[play.google.com/store/apps/details?id=app.echonym](https://play.google.com/store/apps/details?id=app.echonym)**

---

## 👨‍💻 Developer

Built solo by **Abubakar Qazi** — Flutter developer based in Islamabad, Pakistan.

[GitHub](https://github.com/abubakar-qazi) · [LinkedIn](https://linkedin.com/in/abubakar-qazi-6b9934311)
