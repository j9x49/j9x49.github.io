# Blank Page with Domain Display

This repository hosts a **echo page** that displays the domain name of the visitor. It is designed to be used as a placeholder for unused domains in DNS settings.

---

## Features
✅ Displays the called domain (e.g., `www.example.com`)

✅ Completely blank page (minimalist design)

✅ Free hosting on GitHub Pages

✅ Supports custom domains

---

## How to Use

### 1. Deploy to GitHub Pages
1. Fork this repository or create a new one.
2. Upload your `index.html` file (or use the one provided here).
3. Go to **Settings** > **Pages** in your repository.
4. Select the branch (e.g., `main` or `master`) and save.
5. Your site will be live at: https://.github.io//


### 2. Set Up a Custom Domain

#### 1. In your domain registrar (e.g., Namecheap, Cloudflare), add a **CNAME record** for `www` pointing to:

.github.io

Example:
```
www.example.com. CNAME yourusername.github.io.
```

#### 2. Wait for DNS propagation (a few minutes to a few hours).

---

License

This project is open-source and free to use. No attribution is required.

Support

For issues or questions, open an issue in this repository.
