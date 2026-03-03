# 🌐 t3knoid.github.io  

**Personal GitHub Pages Site & Portfolio**

A lightweight, fast, and clean GitHub Pages site portal to showcase my resume, projects, experiments, and technical work.

---

## 🚀 Purpose

This repository powers the public site at **https://portfolio.refol.us**, serving as a central hub for:

- Technical projects and automation tools  
- Homelab architecture and documentation  
- Cloud, DevOps, and infrastructure experiments  
- Résumé and professional links  

---

Here is an updated **README.md** section that cleanly documents the purpose and role of the **CNAME** file in your `t3knoid.github.io` repository. It fits naturally into the existing structure and keeps the concise, modular style you prefer.

You can paste this directly into your README under a new section titled **Custom Domain Configuration**.

---

## 🌐 Custom Domain Configuration (CNAME)

This repository includes a `CNAME` file that defines the **custom domain** served by GitHub Pages. The file contains a single line with the domain name:

```
portfolio.refol.us
```

GitHub Pages uses this file to:

- Associate the repository with the specified custom domain  
- Issue and maintain the SSL certificate for that domain  
- Ensure the site is served at both the apex and `www` variants  
- Prevent GitHub from overwriting domain settings configured in the Pages UI  

The `CNAME` file does **not** modify DNS itself. DNS records must still be configured at the domain registrar. The file simply tells GitHub Pages which domain this site owns and should respond to.

---

## 📁 Repository Structure  
```
/
├── index.html                # Main landing page
├── CNAME                     # Custom domain configuration file
└── README.md                 # You are here
```
