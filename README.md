# 🗓️ Admin Panel for Appointment Management

**Admin Panel for Appointment Management** is a modern web application built with **React** and **TypeScript** that provides an intuitive interface for managing client appointments.  
The system allows administrators to **view, create, update, and cancel** appointments through a sleek calendar interface, ensuring efficient scheduling and organization.

---

<h3 align="center">📸 Project Preview</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/Figrac0/Admin-panel/main/src/assets/1.png" alt="Preview 1" width="800"/><br/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Figrac0/Admin-panel/main/src/assets/2.png" alt="Preview 2" width="800"/><br/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Figrac0/Admin-panel/main/src/assets/3.png" alt="Preview 3" width="800"/><br/>
</p>

---

## ⚙️ Overview

This administrative panel streamlines appointment management by providing:  
- 🗂️ A structured view of all upcoming and past appointments  
- 🧭 Calendar-based filtering for specific dates and time ranges  
- 🔄 Real-time updates of appointment data from the backend  
- ✏️ Tools for editing, confirming, or canceling appointments  
- ⚡ Instant data validation and error handling  

---

## 🚀 Key Features

| Feature | Description |
|----------|-------------|
| 🧩 **Component-Based Architecture** | Built with reusable React + TypeScript components |
| 📅 **Interactive Calendar** | Uses `react-calendar` for intuitive date navigation |
| 🔗 **API Integration** | Fetch, update, and cancel appointments via a REST API |
| ⚙️ **Custom Hooks** | Implements `useHttp` for request handling and data synchronization |
| 🧠 **TypeScript Support** | Strong typing ensures reliability and cleaner development |
| 💾 **Redux-like State Management** | Handles global actions for fetching and updating data |
| 🕵️ **Validation & Error Handling** | Verifies appointment data and manages async request states |

---

## 🧰 Technologies Used

| Category | Tools |
|-----------|-------|
| **Frontend** | React, TypeScript |
| **State Management** | Custom Redux-like structure |
| **Date Management** | Day.js |
| **Calendar UI** | React-Calendar |
| **Networking** | Custom `useHttp` hook (Fetch API) |
| **Styling** | SCSS Modules / CSS3 |

## 🧩 Project Structure
src/ <br/>
├── assets/ # UI images and icons<br/>
├── components/ # Reusable UI components (modals, forms, tables)<br/>
├── hooks/ # Custom hooks (useHttp, useValidation)<br/>
├── pages/ # Main page layout and navigation<br/>
├── store/ # State management logic<br/>
├── types/ # TypeScript type definitions<br/>
├── utils/ # Helper functions and utilities<br/>
└── App.tsx # Root component<br/>
