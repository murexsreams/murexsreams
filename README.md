# 🎵 Murex Streams

Murex Streams is a **music investment and streaming platform** where **artists**, **fans**, and **investors** come together to redefine how music is monetized.  
Artists can upload songs, raise funds like a **mini IPO**, and fans can **invest in music** to earn returns from streaming revenue and ad profits.

---

## 🌟 Vision
Empowering artists to create without limits while giving fans and investors a direct stake in the future of music.

---

## 🚀 Key Features

### 👩‍🎤 For Artists
- Create artist profile
- Upload singles or full albums
- Set fundraising goal per release
- Track investment progress and stream stats
- Sell ad slots on their music profiles
- Withdraw funds to crypto wallet or bank account

### 💸 For Investors / Fans
- Discover trending and upcoming artists
- Invest in songs and earn passive income
- View portfolio and estimated ROI
- Reinvest or withdraw returns directly from the app

### 🎧 Music Streaming
- Stream music directly in-app
- Background audio support
- Shuffle, repeat, and playlist creation
- Stream counts tied to royalty payouts

### 📱 Social Features
- Comment and interact with artists
- Like and favorite songs
- Follow artists for notifications
- Share tracks and portfolios

### 💰 Revenue Streams
- Artist fundraising investments
- Subscription (Premium Users)
- Ads (Google AdMob, Facebook Audience Network, direct brand deals)
- Transaction charges (withdrawals, deposits, and investments)
- NFT or tokenized music ownership (future roadmap)

---

## 🧑‍💻 Tech Stack

### **Frontend (Mobile App)**
- [Expo](https://expo.dev/) (React Native + TypeScript)
- UI Toolkit: TailwindCSS (via NativeWind)
- State Management: Redux Toolkit or Zustand
- Navigation: React Navigation
- Audio Streaming: `expo-av`

### **Backend**
- Node.js + Express.js
- PostgreSQL (with Prisma ORM)
- Socket.IO for real-time updates
- Cloudinary / AWS S3 for file storage
- JWT Auth or OAuth2
- Payment Gateways:
  - USDC on Solana or Ethereum
  - Paystack / Stripe for fiat

---

## 📐 Suggested Database Tables

| Table       | Description |
|-------------|-------------|
| `users` | Artists, investors, and listeners |
| `tracks` | Song metadata and upload info |
| `albums` | Group of tracks |
| `investments` | Record of user investments |
| `wallets` | Linked crypto/fiat wallets |
| `likes` | Track likes |
| `comments` | User comments on tracks |
| `streams` | Stream play count logs |
| `ads` | Artist or platform ad placements |
| `payouts` | Withdrawals and revenue distribution |

---

## 🛠 Installation

### **Prerequisites**
- Node.js (v18 or above)
- PostgreSQL (v14 or above)
- Expo CLI

### **1. Clone Repository**
```bash
git clone https://github.com/your-username/murexstreams.git
cd murexstreams
