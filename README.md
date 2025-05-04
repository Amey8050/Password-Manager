Here's the **README** with added icons to improve its appearance:

````markdown
### 🔐 Password Manager

A **dual-implementation** password manager built using **React**, **TailwindCSS**, and **MongoDB**. Choose between **client-side storage** with **localStorage** or a **database-backed solution** using **MongoDB** for secure password management.

---

### ✨ Features

✅ **Dual Versions** – Two distinct solutions:  
   - **`passsop`** – A lightweight, client-side password manager that stores data in **localStorage** for offline access.  
   - **`passop-mongo`** – A full-stack solution with **React**, **Express.js**, and **MongoDB** for securely storing passwords in a database.

✅ **React-based UI** – Modern, responsive user interface powered by **React** and **TailwindCSS**.  
✅ **Smooth Notifications** – Powered by **React Toastify** for a delightful user experience.  
✅ **Cross-device Sync** (for `passop-mongo`) – Store your passwords securely and access them from multiple devices.

---

### 🚀 How to Run

#### **1️⃣ passsop (Client-side version using localStorage)**

1. Clone the repository:  
   ```bash
   git clone https://github.com/Amey8050/Password-Manager.git
   cd Password-Manager/passsop
````

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm run dev
   ```

4. Open the app in your browser:
   Go to `http://localhost:3000` to start using the **passsop** version.

---

#### **2️⃣ passop-mongo (Full-stack version using MongoDB)**

For **passop-mongo**, you need to open **two separate VSCode tabs** or terminals to run both the frontend and backend.

1. **Frontend** (React):

   🔹 Open one terminal or VSCode tab in the `passop-mongo/client` folder.

   🔹 Install dependencies:

   ```bash
   npm install
   ```

   🔹 Run the React development server:

   ```bash
   npm start
   ```

2. **Backend** (Express + MongoDB):

   🔹 Open another terminal or VSCode tab in the `passop-mongo/server` folder.

   🔹 Install backend dependencies:

   ```bash
   npm install
   ```

   🔹 Start the backend server:

   ```bash
   node server.js
   ```

3. Your full-stack app will be available:

   * **Frontend**: `http://localhost:3000`
   * **Backend**: `http://localhost:5000`

---

### ⚙️ Tech Stack

* **Frontend**:

  * 💻 **React** for building dynamic user interfaces.
  * 🎨 **TailwindCSS** for sleek, responsive design.
  * 🔔 **React Toastify** for smooth notifications.

* **Backend** (For `passop-mongo`):

  * ⚡ **Express.js** for a fast backend API.
  * 🗄️ **MongoDB** for secure storage of passwords.

---

### 📘 Notes

* **`passsop`** uses **localStorage** for storing passwords directly on the client-side, making it an offline solution.
* **`passop-mongo`** stores passwords securely in a **MongoDB** database and can be accessed from multiple devices.
* **For `passop-mongo`**, make sure to run both the frontend and backend simultaneously in **two separate VSCode tabs** or terminals for proper functionality.

---


