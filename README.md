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
