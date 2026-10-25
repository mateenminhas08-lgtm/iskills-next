# 🎓 iSkills Hub — iSkills Next Command Center

> A complete, fully functional, production-ready Single Page Application (SPA) command center for managing course materials, AI prompt sessions, reference videos, tools & spreadsheets, lecture notes, and downloadable documents for the **iSkills Next** course.

![Theme](https://img.shields.io/badge/Theme-Professional%20Blue-0284c7?style=for-the-badge)
![Tech](https://img.shields.io/badge/Architecture-Vanilla%20JS%20%7C%20SPA-0f172a?style=for-the-badge)
![Storage](https://img.shields.io/badge/Storage-LocalStorage%20(Offline%20Ready)-10b981?style=for-the-badge)

---

## 🌟 Key Features

### 1. 🗂️ Module & Sub-Module Architecture
- **Pre-loaded Modules**: SEO, Etsy, AI Agents, Web Coding, General.
- **Nested Sub-Modules**: SEO comes pre-configured with *Niche Research*, *Keyword Research*, *On-Page SEO*, and *Link Building*.
- **Custom Modules**: Create custom modules with icons, or nest them as sub-modules under any parent.

### 2. ⚡ All-in-One Stream Timeline
- Filter items by type: **All**, **AI Chats**, **Videos**, **Tools**, **Notes**, **Files**.
- Sort chronologically (Newest first, Oldest first) or alphabetically.
- Visual timeline with type-specific indicators and badges.

### 3. 🤖 AI Chats Manager
- **Platform Auto-Detection**: Automatically recognizes and brands links from ChatGPT, Claude, Gemini, Groq, DeepSeek, and Perplexity.
- **Pinned Chats**: Pinned chats are highlighted and displayed at the very top of each module stream.
- **View Density Toggle**: Switch between **Cards View** (Compact / Medium / Large grid) and **List View** (clean horizontal rows).

### 4. 🎥 YouTube Reference Videos
- Real-time video metadata extraction via YouTube oEmbed API (`thumbnail_url`, `author_name`, `title`).
- Interactive thumbnail previews with 1-click launch in a new tab.

### 5. 🛠️ Tools & Resource Websites
- Automatic high-res favicon retrieval via Google S2 Favicon API.
- FontAwesome icon override picker for spreadsheets, documents, coding sandboxes, etc.

### 6. 📝 Dual-Mode Notes Editor
- **Rich Text Mode**: Formatting toolbar supporting bold, italic, headings, bullet lists, numbered lists, and blockquotes.
- **Markdown Mode**: Raw markdown editor with instant regex rendering.

### 7. 📁 Hybrid Files & Documents Storage
- Automatic file size detection upon selection.
- **Files < 1MB**: Encoded to Base64 and stored directly inside browser `localStorage` for offline access and download.
- **Files > 1MB**: Safety alert activates to protect browser storage quotas, switching the form to cloud link mode (Google Drive, Dropbox, OneDrive).

### 8. 🏛️ Official Pages & Top Bar Quick Access
- Dedicated repository for official student portals, LMS links, Facebook groups, and shared Google Drive folders.
- Pin official pages to render them globally as quick-access chips across the top header bar.

### 9. 🔍 Real-Time Global Search
- Instant live search scanning across titles, descriptions, tags, notes content, and module names.

### 10. 💾 Persistent Data & JSON Backup
- All data stored under `iskillshub_` keys in `localStorage`.
- Full backup export and restore to ensure your course assets are never lost.

---

## 🚀 Live Demo & Deployment

This application is 100% serverless and requires no build step. To run locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/<username>/iskills-hub.git
   ```
2. Double-click `index.html` to open in any web browser.

### Deploying to GitHub Pages
1. Go to **Settings** > **Pages** in your GitHub repository.
2. Under **Build and deployment** > **Branch**, select `main` and root `/`.
3. Click **Save**. Your site will be live at `https://<username>.github.io/iskills-hub/`.
