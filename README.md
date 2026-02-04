# 🚀 Mobile App Launcher

A lightweight, mobile-first web dashboard designed to be hosted on **GitHub Pages**. This site uses custom URL schemes (Deep Links) to trigger native applications directly from your mobile browser.

## 📱 Features
- **One-Tap Access:** Open Spotify, Google Maps, and more without searching your home screen.
- **Fast & Lightweight:** Built with pure HTML/CSS. No heavy frameworks or JavaScript required.
- **Responsive Design:** Optimized for mobile touch targets and high-speed loading.

## 🛠️ Setup Instructions

1. **Fork or Download:** Copy the `index.html` file to your own GitHub repository.
2. **Customize:** Open `index.html` and edit the `href` attributes to include your favorite apps.
3. **Deploy:** - Go to your repo **Settings**.
   - Navigate to **Pages** on the left menu.
   - Select the `main` branch and click **Save**.
4. **Access:** Your launcher will be live at `https://<your-username>.github.io/<repo-name>/`.

## 🔗 Common App URL Schemes
If you want to add more buttons, here are the links to use:

| App | URL Scheme |
| :--- | :--- |
| **Spotify** | `spotify://` |
| **Google Maps** | `comgooglemaps://` |
| **YouTube** | `youtube://` |
| **Instagram** | `instagram://` |
| **Twitter (X)** | `twitter://` |
| **Discord** | `discord://` |

> **Note:** These links work best on iOS and Android devices. On a desktop browser, they may not respond unless the corresponding desktop application is installed.

## 🎨 Customization
To change the look, simply adjust the CSS variables in the `<style>` block of the `index.html` file. You can swap colors, change the grid layout, or add icons using FontAwesome.

---
*Created for quick-access productivity.*
