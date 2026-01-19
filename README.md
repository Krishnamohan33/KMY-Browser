# Krishnamohan Yagneswaran Browser

A lightweight, native **Win32 + WebView2** browser built for **speed, control, and zero clutter**.

This project is intentionally minimal. It avoids heavy frameworks and focuses on a clean browsing experience using modern Microsoft WebView2 with pure C++ and Win32.

---

## ✨ Key Features (Current Release)

### Core Browser
- Native **Win32 application** written in **C++**
- Powered by **Microsoft WebView2 (Chromium-based)**
- No Electron, no Qt, no heavy frameworks
- Fast startup and low memory footprint
- DPI-aware and stable on resize, maximize, and minimize

### Navigation
- Back, Forward, Reload controls
- Smart address bar:
  - Direct URLs
  - Domain auto-completion (`example.com → https://example.com`)
  - Search fallback (Brave Search)
- Keyboard navigation via address bar (Enter to navigate)

### Dashboard (Home Page)
- Default dashboard shown on startup
- Glass-style UI (safe CSS-based illusion)
- Peacock-feather inspired color palette
- Clear product philosophy and feature overview

### About Page
- Built-in About page
- Author information
- Technology stack description
- External link to official website

### Browsing History
- Automatic capture of visited pages
- Stores page title + URL
- Accessible via **History button**
- Clickable history entries
- In-memory storage (session-based)

### Loading Indicator
- Lightweight loading bar
- Appears on navigation start
- Hides automatically when page load completes

### UI / UX
- Minimal top navigation bar
- Clean, readable typography
- ASCII-safe UI (no emoji or locale-dependent symbols)
- Stable rendering across systems
- Professional layout aligned with native Windows behavior

---

## 🔒 Privacy & Philosophy

- No ads injected by the browser
- No tracking logic implemented
- No telemetry
- No background services
- No data sent anywhere by the application itself

Note: Websites may still load their own content (as with any browser).

---

## 🧠 Technical Details

- Language: **C++**
- Platform: **Windows (x64)**
- UI: **Win32 API**
- Web Engine: **Microsoft WebView2**
- Data Structures:
  - `std::vector` for history management
  - Simple struct-based storage (no database yet)
- Encoding:
  - ASCII-safe UI
  - UTF-8 enforced inside HTML pages

---

## ⚠️ Known Limitations (By Design)

- No tab support (single-view browser)
- No extension system
- No persistent history (clears on restart)
- No bookmarks yet
- No private/incognito mode
- No custom themes toggle

These are intentional to keep the first release clean and stable.

---

## 🛣️ Planned Future Improvements

- Persistent history (file-based)
- Bookmarks
- Incognito / private mode
- Custom title bar
- Optional tab support
- Settings page
- UI theming options
- Portable build and installer

---

## 📦 Build Requirements

- Windows 10 / 11
- Visual Studio (C++ Desktop Development)
- Microsoft WebView2 Runtime
- WebView2 SDK

---

## 👤 Author

**Krishnamohan Yagneswaran**  
Solo developer focused on performance-first tools, games, and native software.

Official website:  
https://www.krishnamohanproductions.com

---

