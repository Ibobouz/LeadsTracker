# Lead Tracker – Mobile Web App (PWA)

**Lead Tracker** is a lightweight Progressive Web App (PWA) designed to help users quickly save and revisit useful links on the go. Whether you're researching on mobile or just want to keep track of pages you like, Lead Tracker lets you save leads in one tap.

##  Features

- 📌 Save URLs directly from your phone
- 📝 Add links manually via input field
- 🗂️ View all saved leads in a clear list
- 🧹 Delete all saved leads at once
- 💾 Data stored locally via browser `localStorage`
- 🌐 Installable as a PWA on Android and iOS

##  How to Use

1. Create a Firebase Database
2. Paste the Database Link in index.js/"databaseURL"
3. Create a Netify Project with the files of this Repository
4. Open the link of your Netify Project in your mobile browser.
5. Add the app to your home screen (via "Add to Home Screen").
6. Launch it like any other app.
7. Use the input field or "Save Current Tab" to store a link.
8. Tap on any saved lead to open it.

## Technologies

- HTML, CSS, JavaScript
- Vite (build tool)
- Google Firebase Database
- PWA with `site.webmanifest` and mobile icons

## 📁 Project Structure

```bash
├── index.html                  # Main HTML page
├── index.js                    # Core logic
├── index.css                   # Styling
├── site.webmanifest            # PWA manifest
├── icon.png / favicons         # App icons for different platforms
├── vite.config.js              # Build configuration
└── package.json                # Project metadata
