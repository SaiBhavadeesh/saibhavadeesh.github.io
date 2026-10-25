# Sai Bhavadeesh & Nivid • Public Website & App Policy Center

Official public website, product portfolio, and legal policy repository for applications developed by **Sai Bhavadeesh** under the **Nivid** brand.

Hosted via [GitHub Pages](https://pages.github.com/) at:  
👉 **https://saibhavadeesh.github.io/**

---

## 📁 Repository Structure

```
saibhavadeesh.github.io/
├── index.html                   # Central Hub & Directory of Apps
├── 404.html                     # Custom 404 Page
│
├── cabletvbook/                 # Cable TV Book App
│   ├── index.html               # Product Overview & Features
│   ├── privacy.html             # Official Privacy Policy
│   ├── privacy-policy.html      # Redirect alias
│   ├── terms.html               # Terms & Conditions
│   └── terms-and-conditions.html# Redirect alias
│
├── foody_cookbook/              # Foody Cookbook App
│   ├── privacy.html
│   └── terms.html
│
├── haiti_bel_air/               # Haiti Bel Air Platform
│   ├── privacy.html
│   └── terms.html
│
└── nivid/                       # Nivid Core Services
    ├── privacy.html
    └── terms.html
```

---

## 🚀 Adding a New App Policy

To add a new app in the future:
1. Create a new directory named after your app: `mkdir my_new_app`
2. Add `my_new_app/privacy.html` and `my_new_app/terms.html`
3. Add a row to the table in root `index.html`
4. Commit and push:
   ```bash
   git add .
   git commit -m "feat: add policies for my_new_app"
   git push origin main
   ```
Your new app policies will immediately be live at:
- `https://saibhavadeesh.github.io/my_new_app/privacy.html`
- `https://saibhavadeesh.github.io/my_new_app/terms.html`

---

## 🔒 Security & Privacy

This repository is publicly hosted to satisfy Google Play Store and Apple App Store public URL verification requirements. It contains only static presentation pages and legal documentation—never private source code or secrets.
