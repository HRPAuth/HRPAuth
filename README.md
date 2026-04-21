# HRPAuth  
*A modern, modular authentication system for Minecraft servers and web applications.*

> **This repository serves as the entry point for the HRPAuth ecosystem.**  
> It contains documentation, release notes, and project overview.  
> **All source code lives in the frontend and backend repositories.**

---

## 📦 Repository Structure

HRPAuth consists of three coordinated repositories:

| Repository | Description |
|-----------|-------------|
| **[HRPAuth-Web](https://github.com/HRPAuth/HRPAuth-Web)** | Frontend (React + TypeScript + MUI) |
| **[HRPAuth-Backend-PHP](https://github.com/HRPAuth/HRPAuth-Backend-PHP)** | Backend API service (PHP 8.2+) |
| **[HRPAuth](https://github.com/HRPAuth/HRPAuth)** | Main repository (documentation + releases) |

---

## ✨ Overview

HRPAuth is a lightweight, extensible authentication system designed to support:

- User registration and login  
- Email verification codes  
- TOTP-based two‑factor authentication  
- Token-based authentication  
- A modern, responsive web interface  
- Self-hosted deployment with full control  

The project is currently **experimental** and under active development.

---

## 🧩 System Architecture

```
[HRPAuth-Web]  ←→  [HRPAuth-Backend-PHP]  ←→  [MySQL]
       ↑
       │
       └──────────→  [HRPAuth Main Repository]
```

- **Frontend**: User-facing UI  
- **Backend**: REST API for authentication  
- **Database**: User, verification, and TOTP storage  
- **Main repo**: Documentation and releases  

---

## Requirements
  PHP (>=8.1 is recommended, other versions seems also excutable)  
  Web server (default Apache http server, because the .htaccess file is prepared for apache)  
  MySQL (>=8.0 is recomended, other versions seems also excutable)  
  *You may transform the .htaccess file into Nginx or others directives form.
## Quick start
  1.Download the newest [release](https://github.com/HRPAuth/HRPAuth/releases/latest)  
  2.Uncompress
  'tar -xzvf ./your-release-file'  
  3.Place the uncompressed folder in your PHP web server

---

## 📚 Documentation

- **API Documentation**: `api-doc.json` in the backend repository(For code agent)  
- **Deployment Guide**:   Please visit [Wiki](https://github.com/HRPAuth/HRPAuth/wiki)

---

## 🛠 Technology Stack

### Frontend
- React  
- TypeScript  
- MUI  
- Vite  

### Backend
- PHP 8.2+  
- MySQL  
- Redis / Memcached  

---

## 🗺 Roadmap
✅Fully supported | 🟢 Partial supported | 🟡 Being tested | 🟥 Pending supported
- ✅ Authme and blessing-skin support
- ✅ Authlib-injector support(yggdrasil-api)
- 🟢 OAuth2 compatibility layer
- 🟡 Luckperms support
- 🟥 Internationalization (i18n)  
- 🟥 Admin dashboard  
- 🟥 Plugin ecosystem (Minecraft / Webhooks)  

---

## 🤝 Contributing

Contributions are welcome:

- Bug reports  
- Feature requests  
- Pull requests  
- Documentation improvements  

Please open an issue to start a discussion.

---

## 📄 License

HRPAuth is licensed under the **GNU Affero General Public License v3.0 (AGPLv3)**.

This ensures:

- The project remains free and open-source  
- Any modified version deployed over a network must also publish its source code  

See the full license text in:  
**`[Looks like the result wasn't safe to show. Let's switch things up and try something else!]`**

---

## ⭐ Support the Project

If you find HRPAuth useful, please consider starring the repositories:

- [HRPAuth](https://github.com/HRPAuth/HRPAuth)  
- [HRPAuth-Web](https://github.com/HRPAuth/HRPAuth-Web)  
- [HRPAuth-Backend-PHP](https://github.com/HRPAuth/HRPAuth-Backend-PHP)

Your support helps the project grow.
