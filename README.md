# 📋 TodoApplication – Ruby on Rails

This is a beginner-level Todo Application built using Ruby on Rails, designed to demonstrate the **MVC (Model-View-Controller)** architecture and basic CRUD functionality with a Bootstrap-enhanced UI.

---

## 🚀 Features

- Add, edit, view, and delete Todo items
- Each Todo has:
  - `title` (string)
  - `description` (text)
  - `completed` (boolean)
- Fully functional CRUD interface generated via Rails scaffold
- Responsive UI styled using Bootstrap 5

---

## 📦 Tech Stack

- **Language:** Ruby 3.x
- **Framework:** Rails 7.x / 8
- **Database:** SQLite3 (development)
- **Frontend:** HTML, ERB templates
- **Styling:** Bootstrap 5 (via Importmap and CDN)

---

## 🧱 MVC Architecture Overview

- **Model:** `Todo` – Handles data structure and database interaction.
- **View:** `app/views/todos/` – Contains ERB templates for UI rendering.
- **Controller:** `TodosController` – Handles application logic and request/response flow.

---

## 📚 Learning Log

### ✅ Day 11: Rails Introduction & Setup

**Topics Covered:**
- Introduction to Rails
- Setting up Rails environment

**Activities Completed:**
- Installed Ruby and Rails
- Created a `hello_rails` starter app
- Pushed basic Rails app to GitHub
- Took and uploaded a running app screenshot

**Resources Used:**
- 📺 *Rails Tutorial for Beginners (1:30 hr)*

---

### ✅ Day 12: MVC Architecture & Bootstrap Integration

**Topics Covered:**
- Understanding the MVC Architecture in Rails
- Building a full Todo CRUD app using MVC pattern
- Styling Rails views using Bootstrap 5

**Activities Completed:**
- Created a model (`Todo`), controller, and views manually using Rails scaffold
- Rendered dynamic content with ERB
- Integrated Bootstrap 5 via Importmap
- Styled forms, buttons, alerts, and layouts

---

## 🔧 Setup Instructions

1. **Clone the repo:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/todo_application.git
   cd todo_application
