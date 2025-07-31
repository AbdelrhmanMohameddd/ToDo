# ✅ ToDO - Flutter App

A simple and efficient **To-Do List App** built with Flutter.  
This project is part of the NTI training and is designed to help users manage their daily tasks with ease and productivity.

---

## ✨ Features

- 📝 Add, Edit, and Delete Tasks
- 📅 Mark Tasks as Completed or Pending
- 📌 Task Priority Management
- 🔔 Task Reminder (Optional)
- 🌙 Light & Dark Theme Support
- 💾 Local Data Persistence with `sqflite` / `Hive`
- 🧩 Clean and Organized Codebase

---

## 🧱 Project Structure

```bash
lib/
├── core/             # Themes, constants, helpers
├── features/
│   ├── tasks/        # Task logic: UI, Cubit/Bloc, Model
│   └── shared/       # Reusable widgets and services
├── data/             # Local database or mock APIs
└── main.dart

