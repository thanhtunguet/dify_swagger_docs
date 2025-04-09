# 📘 Dify Swagger UI (Static Site)

This repository hosts a static web page to view the Dify API documentation using Swagger UI.

---

## 🔍 Overview
This site loads the Dify OpenAPI spec from `/assets/swagger.yaml` and renders an interactive Swagger UI interface for API exploration and testing.

---

## 📁 Project Structure
```
/
├── index.html              # Swagger UI loader
├── assets/
│   └── swagger.yaml        # OpenAPI YAML spec for Dify API
```

---

## 🌐 Live Preview
If deployed to GitHub Pages, access it at:
```
https://thanhtunguet.github.io/dify_swagger_docs
```

Or serve locally:
```bash
python3 -m http.server 8080
# Then visit http://localhost:8080
```

---

## 🔧 Customization
To update the API documentation:
- Edit `assets/swagger.yaml`
- Reload the browser to see changes

You can customize the UI theme, layout, or branding by modifying `index.html`.

---

## 🚀 Deployment
Use GitHub Pages, Vercel, Netlify, or any static web hosting service.

For GitHub Pages:
1. Push to main branch
2. Enable Pages under repo Settings → Pages → Source = main → `/ (root)`

---

## 📄 License
MIT License © 2025 [thanhtunguet]