# ✅ TaskFlow — To-Do List Web Application

![TaskFlow Preview](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> A fully client-side, production-ready task management app with dark mode, priority levels, filters, inline editing, and `localStorage` persistence — built with pure HTML, CSS, and JavaScript.

---

## 🔗 Live Demo

🔗 Live Demo: https://aryanrawat00.github.io/todo-list-app/

---

## 📸 Screenshots

| Light Mode | Dark Mode |
|---|---|
| ![Light Mode](screenshots/light.png) | ![Dark Mode](screenshots/dark.png) |

---

## ✨ Features

- ✅ **Add Tasks** — Type and press `Enter` or click `Add`
- ✏️ **Edit Tasks** — Inline editing without page reload
- 🗑️ **Delete Tasks** — Remove individual tasks instantly
- ☑️ **Complete Tasks** — Custom animated checkbox
- 🌙 **Dark / Light Mode** — Toggle with persistence via `localStorage`
- 🔴🟡🟢 **Priority Levels** — High, Medium, Low with color badges
- 📊 **Stats Bar** — Live count of Total / Active / Done tasks
- 🔍 **Filter Tabs** — View All / Active / Completed tasks
- 🧹 **Clear Completed** — Remove all done tasks at once
- 🍞 **Toast Notifications** — Visual feedback for every action
- 💾 **localStorage Persistence** — Tasks survive page refresh
- 📱 **Fully Responsive** — Works on all screen sizes

---

## 🗂️ Project Structure

```
todo-list-app/
│
├── index.html          # Main application file (all-in-one)
├── README.md           # Project documentation
├── LICENSE             # MIT License
│
└── screenshots/        # App preview images
    ├── light.png
    └── dark.png
```

---

## 🚀 Getting Started

### Option 1: Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/aryanrawat00/todo-list-app.git

# 2. Navigate into the folder
cd todo-list-app

# 3. Open index.html in your browser
# Double-click index.html, OR use VS Code Live Server extension
```

### Option 2: Use Live Server (VS Code)
1. Install the **Live Server** extension in VS Code
2. Open the project folder
3. Right-click `index.html` → **Open with Live Server**

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, animations, CSS variables for theming |
| **Vanilla JavaScript** | DOM manipulation, event handling, state management |
| **localStorage API** | Persistent data storage in the browser |

**No frameworks. No dependencies. No build step required.**

---

## 🧠 Key Concepts Demonstrated

- **DOM Manipulation** — Dynamic task list rendering with `innerHTML` and `createElement`
- **Event-Driven Programming** — `onclick`, `onchange`, `keydown` event listeners
- **CSS Custom Properties** — Theme switching via `:root` variable swapping
- **localStorage** — Reading and writing JSON data for persistence
- **State Management** — Central `tasks` array with a single `render()` function
- **Responsive Design** — Flexbox layout with `@media` query breakpoints
- **CSS Animations** — `@keyframes slideIn` for new task entrance
- **Security** — HTML escaping to prevent XSS injection

---

## 📋 How to Use

1. **Add a task** — Type in the input field → select priority → press `Enter` or `Add`
2. **Complete a task** — Click the checkbox on the left
3. **Edit a task** — Click the ✏️ button → edit text → press `Enter` or 💾
4. **Delete a task** — Click the 🗑️ button
5. **Filter tasks** — Use the All / Active / Completed tabs
6. **Toggle dark mode** — Click the 🌙 button in the top right
7. **Clear done tasks** — Click **Clear completed** in the footer

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Aryan Rawat**
- GitHub: [@aryanrawat00](https://github.com/aryanrawat00)
- LinkedIn: [Aryan Rawat](https://linkedin.com/in/aryan-rawat-2aa8753a2)

---

## 🏆 Acknowledgements

- Built during internship at **VaultofCodes.in** (Jun – Aug 2025)
- Submitted as internship capstone project

---

*If you found this project helpful, please ⭐ star the repository!*
