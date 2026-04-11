# Hari's Fresh Corner — Website System

## Files in This Package

| File | Purpose |
|------|---------|
| `index.html` | Public website (what customers see) |
| `admin.html` | Admin editor (your private control panel) |
| `site-config.json` | All your content in one place |
| `README.md` | This guide |

---

## How to Use

### Editing Your Site
1. Open `admin.html` in your browser (just double-click)
2. Login with password: **admin123** (change it in Settings after first login)
3. Edit anything: colors, fonts, products, prices, images, texts
4. Click **Save All Changes**
5. Click **Download site-config.json**
6. Upload that downloaded file to your GitHub repo

### Deploying to GitHub Pages
1. Create a GitHub account at github.com (free)
2. Create a new repository, name it `your-shop` (anything)
3. Upload `index.html` and `site-config.json` to the repo
4. Go to Settings → Pages → Source: "main branch"
5. Your site is live at `https://yourusername.github.io/your-shop`

### ⚠️ Security Notes
- **Do NOT upload `admin.html` to your public GitHub repo**
  Keep it on your computer only, or in a private repo
- The `index.html` source code reveals no content — everything loads from JSON
- Change the admin password after first use

### Adding Product Images
Upload images to any free host:
- **GitHub itself**: upload to your repo → right-click → Copy image address
- **Imgur.com**: free, no account needed
- **Cloudinary.com**: free tier, auto-resizes

Paste the image URL into the product's Image URL field in the admin panel.

### Nepali / Devanagari Fonts
Go to **Admin → Fonts → Enable Devanagari Font**
Then type Nepali text anywhere in your content fields.

---

## Default Password
`admin123` — Change it in Admin → Settings immediately!
