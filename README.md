Below is the **complete `README.md` file** you can **copy-paste directly** into your repository root.
(No email block used — this is a GitHub README, as required.)

---

```md
# TelcoSec Asset Guardian 🔐📡

![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?logo=vite)
![React](https://img.shields.io/badge/React-18.x-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

**TelcoSec Asset Guardian** is a professional-grade **Asset Management Tool** built for **Telecom Security Testing Labs**.  
It enables secure, traceable, and role-based management of **internal lab assets** and **OEM testing devices**.

Designed for real-world certification, compliance, and R&D lab environments.

---

## 🚀 Key Features

### 🔹 Internal Asset Management
- Manage IT & non-IT lab assets (PCs, routers, firewalls, tools, etc.)
- Asset ownership, status, and lifecycle tracking
- Centralized dashboard visibility

### 🔹 OEM Product Management
- Track devices and support items received from OEMs
- PO, Invoice, testing status, and return tracking
- Suitable for ITSAR / certification labs

### 🔹 Role-Based Access Control
- **Admin**: Full control & configuration
- **Security Guard**: Entry & movement logging

### 🔹 Modern UI
- Clean React-based interface
- Interactive tables & modals
- Responsive layout

---

## 🛠 Technology Stack

| Layer | Technology |
|-----|-----------|
| Frontend | React + TypeScript |
| Build Tool | Vite |
| Charts | Recharts |
| State | Local Store (Mock Data) |
| AI Integration | Gemini API |
| Hosting | GitHub Pages |

---

## 📁 Project Structure

```

telcosec-asset-guardian/
├── index.html
├── index.tsx
├── App.tsx
├── types.ts
├── constants.tsx
├── metadata.json
├── package.json
├── vite.config.ts
├── .gitignore
├── .env
├── README.md
├── LICENSE
├── services/
│   └── geminiService.ts
├── store/
│   └── mockData.ts
├── components/
│   ├── Layout.tsx
│   ├── Dashboard.tsx
│   ├── AssetTable.tsx
│   ├── AssetModal.tsx
│   ├── Login.tsx
│   └── StaffManagement.tsx
└── screenshots/
├── dashboard.png
├── asset-table.png
├── asset-modal.png
└── login.png

````

---

## ⚙️ Local Setup

### 1️⃣ Install Dependencies
```bash
npm install
````

### 2️⃣ Environment Configuration

Create a `.env` file:

```env
VITE_GEMINI_API_KEY=your_actual_api_key
```

⚠️ `.env` is excluded via `.gitignore`

---

### 3️⃣ Run Locally

```bash
npm run dev
```

Open:

```
http://localhost:5173
```

---

## 📸 Screenshots

### Dashboard Overview

![Dashboard](screenshots/dashboard.png)

### Asset Management Table

![Asset Table](screenshots/asset-table.png)

### Add / Edit Asset

![Asset Modal](screenshots/asset-modal.png)

### Login & Role Selection

![Login](screenshots/login.png)

---

## 🌍 Live Demo (GitHub Pages)

🔗 **[https://YOUR_USERNAME.github.io/telcosec-asset-guardian/](https://YOUR_USERNAME.github.io/telcosec-asset-guardian/)**

### Deployment Steps

```bash
npm run build
npm run deploy
```

Ensure `vite.config.ts` includes:

```ts
base: '/telcosec-asset-guardian/'
```

---

## 🔐 Security Notes

* API keys stored securely using environment variables
* `.env` and `node_modules` excluded from GitHub
* No hardcoded secrets

---

## 🧩 Planned Enhancements

* Database integration (PostgreSQL / MongoDB)
* Authentication & audit logs
* QR / Barcode asset tagging
* PDF & Excel report export
* Compliance mapping (CRA / ITSAR / ISO)

---

## 👨‍💻 Author

**Saurav (Kakashi)**
Cybersecurity | Telecom Security Testing | R&D
Built for real-world telecom lab operations

---

## 📜 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

```

```
