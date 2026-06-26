# 📝 NoteKeeper — PWA Notes App

A simple, clean notes app built as a Progressive Web App (PWA).  
Works on Android, iOS, and desktop. Can be published on Google Play Store.

---

## 📁 Project Files

| File | Purpose |
|------|---------|
| `index.html` | Main app — all UI and logic |
| `manifest.json` | App name, icon, colors for Play Store |
| `sw.js` | Service Worker — makes app work offline |
| `icon-192.png` | App icon (small) — add manually |
| `icon-512.png` | App icon (large) — add manually |
| `privacy-policy.html` | Privacy policy page — required for Play Store |

---

## ✨ Features

- Write and save notes
- Delete notes
- Color label for each note
- Works offline
- Mobile-first design
- Light theme, clean UI

---

## 🚀 How to Publish on Google Play Store

### Step 1 — Host on Netlify (Free)
1. Go to [netlify.com](https://netlify.com) and sign up
2. Create a folder with all project files
3. Drag and drop the folder on Netlify dashboard
4. Your app URL will be: `yourapp.netlify.app`

### Step 2 — Generate APK using PWABuilder (Free)
1. Go to [pwabuilder.com](https://pwabuilder.com)
2. Enter your Netlify URL
3. Click **Start** → Select **Android**
4. Click **Download Package** → you get a `.aab` file

### Step 3 — Upload to Google Play Store ($25 one-time)
1. Go to [play.google.com/console](https://play.google.com/console)
2. Create a developer account ($25 one-time fee)
3. Click **Create App** → fill in details
4. Upload your `.aab` file
5. Add screenshots, icon, description
6. Submit for review (takes 2-3 days)

---

## 📋 Play Store Checklist

- [ ] App works without crashes
- [ ] Privacy Policy URL added
- [ ] App icon 512x512 PNG ready
- [ ] At least 2 screenshots (1080x1920)
- [ ] App description written
- [ ] Content rating form filled
- [ ] Category set to: **Productivity**

---

## 🔒 Privacy Policy

This app does NOT collect any user data.  
All notes are stored locally on the device using localStorage.  
No internet connection required after first load.

---

## 🛠 Tech Used

- HTML, CSS, JavaScript (vanilla — no frameworks)
- Web App Manifest
- Service Worker (for offline support)

---

## 📞 Support

For any issues, contact the developer before leaving a bad review.

---

*Made with ❤️ — NoteKeeper v1.0*
