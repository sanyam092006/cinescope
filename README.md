# 🎬 CineScope — Movie & Anime Search

> Search millions of movies and anime, discover your next obsession, and save them to your personal watchlist.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Built with HTML/CSS/JS](https://img.shields.io/badge/Built%20with-HTML%2FCSS%2FJS-1f425f?logo=javascript)](https://developer.mozilla.org/)

## ✨ Features

- 🔍 **Search Movies & Anime** - Millions of titles
- 📚 **Browse & Filter** - Sort by year, type, rating
- ⭐ **Personal Watchlist** - Save locally
- 🎭 **Detailed Info** - Plot, cast, ratings
- 📺 **Streaming Links** - Find where to watch
- 🎨 **Beautiful UI** - Dark theme with animations
- 📱 **Fully Responsive** - Mobile, tablet, desktop

## 🚀 Quick Start

### 1️⃣ Get Your FREE API Keys

**OMDB API (Movies - Required):**
- Visit: https://www.omdbapi.com/apikey.aspx
- Enter email, select "Free"
- Confirm via email
- Copy your API key

**RapidAPI Key (Streaming - Optional):**
- Visit: https://rapidapi.com/movie-of-the-night-movie-of-the-night-default/api/streaming-availability
- Sign up free
- Subscribe to test
- Copy your API key from headers

### 2️⃣ Setup Instructions

1. **Download or Clone**
   ```bash
   git clone https://github.com/sanyam092006/cinescope.git
   cd cinescope
   ```

2. **Open `index.html` in your editor**

3. **Find and Replace These Lines** (around line 650-651):
   ```javascript
   const OMDB_KEY = '7a425af5';  // ← REPLACE WITH YOUR KEY
   const RAPID_KEY = '';         // ← PASTE YOUR KEY HERE (optional)
   ```

4. **Save the file**

5. **Open in Browser**
   - Double-click `index.html` OR
   - Run: `python -m http.server 8000` and visit `http://localhost:8000`

6. **Start Searching!** 🎉

## 🔒 API Key Security

- ✅ **Client-side only** - No backend needed
- ✅ **LocalStorage** - Your watchlist stays private
- ⚠️ **Keys in code** - Fine for free read-only APIs
- 🔐 **Never share keys** - Regenerate if exposed

### Best Practices
- Keep API keys private
- Monitor usage on RapidAPI dashboard
- Free tiers have rate limits

## 🎮 How to Use

**Search Movies/Anime:**
- Select tab (🎬 Movies or ⛩ Anime)
- Type title in search box
- Use filters to narrow results

**Manage Watchlist:**
- Click "+ List" to save items
- Click "Watchlist" button to view
- Click "✕" to remove

**View Details:**
- Click "Details" or card
- See full info + streaming platforms
- Add to watchlist from modal

## 🛠 Technologies

- **Frontend**: HTML5, CSS3, JavaScript
- **APIs**: 
  - OMDB (Movies)
  - Jikan (Anime)
  - RapidAPI (Streaming)
- **Storage**: LocalStorage

## 📄 License

MIT License - See LICENSE file

## 🙏 Credits

- [OMDB API](https://www.omdbapi.com/)
- [Jikan API](https://jikan.moe/)
- [RapidAPI](https://rapidapi.com/)

⭐ **If useful, please star this repo!**
