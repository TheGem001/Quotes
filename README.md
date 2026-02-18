# ❝ Daily Inspiration (Quotes)

**A Minimalist Source of Wisdom & Motivation**

![Version](https://img.shields.io/badge/version-1.0-blueviolet)
![Status](https://img.shields.io/badge/status-live-success)
![Design](https://img.shields.io/badge/design-Glassmorphism-A78BFA)

**Daily Inspiration** is a beautifully designed web application that delivers curated quotes to uplift your day. Built with a focus on aesthetics, it features a modern **Glassmorphism** UI, ambient background animations, and seamless interaction.

🔗 **Live Demo:** [https://thegem001.github.io/Quotes/](https://thegem001.github.io/Quotes/)

---

## ✨ Features

### 🎨 Aesthetic UI/UX
* **Glassmorphism Design:** A premium, translucent card layout (`glass-card`) with blur effects.
* **Ambient Backgrounds:** Animated, pulsing orbs that create a calming atmosphere.
* **Typography:** Elegant pairing of *DM Serif Display* for quotes and *Inter* for UI elements.

### ⚡ Smart Functionality
* **Auto-Refresh:** Automatically fetches a new quote every **60 seconds** with a visual progress bar.
* **Share Ready:** Uses the **Web Share API** to instantly share quotes to social media or messaging apps.
* **One-Click Copy:** Copy quotes to your clipboard instantly with a toast notification feedback.
* **Offline Fallback:** Includes a robust local database of timeless quotes (Steve Jobs, Einstein, etc.) to ensure the app works even without an internet connection.

### 🛠️ API Integration
* **Dynamic Content:** Fetches fresh data from `dummyjson.com/quotes/random` for endless variety.
* **Loading States:** Smooth fade-in/fade-out animations during data fetching.

---

## 💻 Tech Stack

* **Core:** HTML5, Vanilla JavaScript (ES6+)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN)
* **Icons:** [Phosphor Icons](https://phosphoricons.com/)
* **Fonts:** Google Fonts
* **Architecture:** Single Page Application (SPA)

---

## ⚙️ How to Run Locally

Since this project uses a standard HTML structure with CDN links, no build process is required.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/thegem001/Quotes.git](https://github.com/thegem001/Quotes.git)
    ```
2.  **Run the App:**
    Simply open `index.html` in your browser.
    
    *Note: For the best experience (and to avoid CORS issues with some APIs), it is recommended to use a local server like "Live Server" in VS Code.*

---

## 📂 Project Structure

* `index.html`: The complete application codebase. It contains:
    * **Tailwind Config:** Custom color palette (`surface`, `primary`, `onPrimary`) and animations.
    * **Application Logic:** Fetching logic, timer management, and clipboard handling.
    * **UI Structure:** The responsive layout and glass effect styles.

---

## 👥 Credits

**Created By:**
* Saqib Zahid (TheGem001)

*Powered by Gem Labs*
