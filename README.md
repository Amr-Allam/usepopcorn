# 🍿 usePopcorn
A movie discovery and rating web application where users can search films, view details, rate movies, and maintain a watched list — built with React, reusable components, and custom hooks.

---

### 🚀 Live Demo  
👉 https://usepopcorn-site.vercel.app/

---

### 🧩 Features  

- 🔍 **Search for movies** using the OMDb API  
- 🎬 **View full movie details** — plot, actors, director, genre, and runtime  
- ⭐ **Rate movies** using a custom star rating component  
- 📁 **Add movies to a watched list** with your own rating  
- 🗑️ **Remove movies** from your watched list  
- 📊 **Watched summary**:  
  - Average IMDb rating  
  - Average user rating  
  - Average runtime  
- 💾 **LocalStorage persistence** for watched movies  
- ⌨️ **Keyboard shortcuts**  
  - *Enter* → focus the search bar  
  - *Escape* → close movie details  
- 📦 **Collapsible UI panels** for search results and watched movies  
- ⚡ Fast, reactive UI built with modern React hooks  

---

### 🧠 What I Learned  

- Building **React components** and structuring a full UI  
- Creating **custom hooks** to organize logic:
  - `useMovies` → fetch & manage movie data  
  - `useLocalStorageState` → persistent state synced with LocalStorage  
  - `useKey` → reusable keyboard event listener logic  
- Handling UI logic with `useState`, derived state, and event handlers  
- Using `useEffect` for:
  - Fetching API data  
  - Updating `document.title`  
  - Syncing UI with state changes  
- Using `useRef` to:
  - Track rating decision counts  
  - Manage input focus  
- Fetching movie details via the OMDb API  
- Conditional rendering & handling loading/error states  
- Improving UX with clean component composition  

---

### 🛠️ Tech Stack  

- **React (Hooks: useState, useEffect, useRef)**  
- **Custom React Hooks**  
- **JavaScript (ES6+)**  
- **HTML5 / CSS3**  
- **OMDb API**  
- **LocalStorage API**

