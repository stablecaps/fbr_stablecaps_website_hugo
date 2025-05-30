# Stablecaps Ltd – Hugo Site (PaperMod Theme)

Stablecaps: DevOps, SRE, and platform engineering — tuned for velocity, resilience, and DevEx.

Overview:
Stablecaps website repo built with **Hugo** and the **PaperMod** theme.

---

## 🚀 Quick Start

### 1. Install Hugo (Extended Version Recommended)

```bash
# Download latest extended release (Linux 64-bit shown here)
wget https://github.com/gohugoio/hugo/releases/download/v0.125.6/hugo_extended_0.125.6_Linux-64bit.tar.gz
tar -xzf hugo_extended_0.125.6_Linux-64bit.tar.gz
sudo mv hugo /usr/local/bin/
```

### 2. Run Locally

```bash
cd stablecaps_site
hugo server
```

Visit `http://localhost:1313` to preview the site.

---

## 🌐 Deploying to Netlify

### 1. Create GitHub Repo

```bash
cd stablecaps_site
git init
git remote add origin https://github.com/yourusername/stablecaps-site.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

### 2. Connect to Netlify

- Go to [Netlify](https://netlify.com/)
- Create a new site from Git
- Select your GitHub repo
- Set the following build settings:

```
Build command: hugo
Publish directory: public
Hugo version: 0.147.6 (Extended)
```

- Add custom domain and enable HTTPS (free via Let’s Encrypt)

---

## 🧱 Content Structure

- `content/about.md` – About page (company framing)
- `content/services.md` – Freelance offerings (optional)
- `content/posts/roi-climbing-plants.md` – First blog post using structured decision logic

---

## 🧠 Notes

- You don’t need to make the GitHub repo public — Netlify supports private repos
- All personal info has been omitted as per your privacy settings

Happy building!
