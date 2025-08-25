# 💰 Expense Management System

The **Expense Management System** is a web application built with **Angular** that helps users manage shared expenses within groups. It ensures transparency by automatically calculating how much each user owes or is owed, while supporting secure authentication and role-based access.

---

## 🚀 Features

- 👥 **Group Management**: Create groups and add members.
- 💵 **Expense Tracking**: Add expenses and view all groups you are part of.
- ⚖️ **Auto Balance Calculation**: System automatically calculates how much each user owes.
- 🔐 **Authentication**: JWT-based login & route protection.
- 🛡️ **Roles**: Supports both **Admin** and **User** roles.
- ⚠️ **Error Handling**: Exceptions managed using Angular HTTP Interceptor.
- 📱 **PWA Support**: Configured with `ngsw-config.json` for service worker support.

---

## 🏗️ Project Structure

The app follows a **feature-first structure** with clear separation of concerns:

- **Auth** → JWT-based authentication, middleware for protecting routes.
- **Backend** →
  - `server.js` → Express API.
  - `authMiddleware.js` → Security.
  - `serverData.json` → Mock persistence.
- **Group** → Create groups & list user groups.
- **Expense** → Add expenses, calculate balances.
- **Core** → HTTP interceptor & authentication guards.
- **Shared** → Reusable Angular components, services, and utilities.
- **Build/Deploy** → Production build artifacts inside `dist/expense-tracking-project`.
- **Routing** → Authentication, group listing, and expense logging with guards.

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository

````bash
git clone <repository_url>
cd expense-management-system


Perfect 👍 You want me to give you the Installation & Setup part (with commands) in README.md format inside a code block.
Here it is:

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone <repository_url>
cd expense-management-system
```
2️⃣ Install Dependencies

```bash
npm install
```

3️⃣ Run in Development Mode

Start Angular app:

```bash
ng serve
```

Start JSON Server:

```bash
npm run json
```

4️⃣ Run Production Build

Build Angular app:

```bash
ng build --prod
```

Start server with production build:

```bash
node server.js
````
