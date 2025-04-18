## 📘 EduTrack Pro – Public API Documentation

Welcome to the public documentation for the **EduTrack Pro API** – a secure backend system for managing users, courses, enrollments, and analytics across educational institutions.

🔗 **Live URL:**  
📄 [https://your-username.github.io/edu-track-api-docs](https://rrc-2024-om.github.io/EDU-TRACK-DOC/)

> ⚠️ Replace `RRC-2024-OM` with your actual GitHub username.

---

### 📌 What Is This?

This GitHub Pages site hosts the full **OpenAPI specification** and **interactive documentation** for the EduTrack Pro REST API, built using [Redoc](https://redocly.com/cli/). This documentation is auto-generated from the API project’s Swagger JSDoc comments.

---

### 🚀 Features

- 📖 Full API reference with role-based descriptions
- 🔐 Authentication and authorization flows
- 📬 Request/response examples
- 📊 Analytics and progress tracking endpoints
- 🏫 Multi-role access: Super Admin, Institution Admin, Teacher, Student, Parent

---

### 🛠 How Was This Built?

1. **Generate OpenAPI Spec in EduTrack Pro API Project**
   ```bash
   npm run generate-docs
   ```
   This creates:
   - `openapi.json`
   - `api-docs/index.html`

2. **Copy Output to This Repo**
   Copy everything inside `api-docs/` into this repo’s root:
   ```bash
   cp -r ../edu-track-api/api-docs/* ./
   ```

3. **Deploy on GitHub Pages**
   - Go to **Settings > Pages**
   - Source: `main` branch, folder: `/ (root)`
   - Save and publish

---

### 🧩 How to Update Docs

When you make changes to your API:
```bash
cd ../edu-track-api
npm run generate-docs
cp -r api-docs/* ../edu-track-api-docs/
cd ../edu-track-api-docs
git add .
git commit -m "🔄 Update API docs"
git push
```

---

### 📦 Related Projects

- 🔐 [EduTrack Pro API Repo](https://github.com/RRC-2024-OM/Edu_Track_Pro) – Full backend source code
- 📑 [FastAPI Docs](https://github.com/tiangolo/fastapi) – Reference project for clean documentation layout

---

### 👨‍🏫 About EduTrack Pro

A backend-first educational management system that supports:
- Multi-institution management
- Secure role-based access
- Bulk imports via CSV
- Real-time progress tracking
- Exportable analytics (CSV/PDF)

---

If you found this project useful or want to contribute, feel free to fork the repo, create issues, or open a PR! 🚀

---
