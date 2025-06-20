# ZeroTrustErrorPages by 1945VN

A modern collection of static HTML error pages (403, 404, 500, etc.) designed specifically for Zero Trust environments. Built and maintained by **1945VN**, this project aims to provide secure, minimal, and user-friendly feedback to users who encounter access restrictions or system errors.

---

## 🚀 Features

- ✨ Clean, responsive design
- 🔐 Security-focused messaging (Zero Trust context)
- 📄 Includes common errors: 403 Forbidden, 404 Not Found, 500 Server Error
- 🌐 Easy to deploy with:
  - GitHub Pages
  - Cloudflare Access
  - NGINX / Apache / any static server

---

## 📂 Pages Included

| Page | Description            |
|------|------------------------|
| `403.html` | Forbidden – Access Denied |
| `404.html` | Page Not Found            |
| `500.html` | Server Error               |

---

## 🛠️ Usage

### Option 1: GitHub Pages

1. Fork or clone this repository
2. Enable GitHub Pages in your repo settings
3. Set source to `main` and root directory `/`
4. Visit your site at: `https://your-username.github.io/ZeroTrustErrorPages`

### Option 2: Use with Cloudflare Access

1. Add these pages to your internal app or hostname
2. Configure Cloudflare Tunnel and Access policy
3. Set error page paths in your web server (or Page Rules)

---

## 📸 Screenshot Preview

> *(Insert screenshot of 403.html, 404.html here for visual reference)*

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).  
© 2025 [1945VN](https://github.com/1945VN)

---

## 🙌 Credits

Created and maintained by **1945VN**  
Inspired by real-world Zero Trust deployment needs
