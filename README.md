# Employee Task Tracker

A simple and responsive **Employee Task Management Dashboard** built using **React (Vite)** and **Tailwind CSS**.  
This application helps track tasks assigned to each employee with filtering, status updates, and a clean UI.

---

## 🚀 Features

### 🔹 Employee Management
- List of employees with role and task count
- Select a specific employee to view only their tasks

### 🔹 Task Management
- Add new tasks with:
  - Title  
  - Description  
  - Due date  
  - Assignee  
  - Status (Pending / In Progress / Completed)
- Delete tasks
- Real-time filtering of tasks by status

### 🔹 UI/UX
- Clean dark-mode interface  
- Status pills with color-coded labels  
- Responsive layout for desktop & mobile  
- Tailwind CSS for styling

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **React (Vite)** | Frontend framework |
| **Tailwind CSS** | Styling |
| **JavaScript (ES6+)** | Logic |
| **JSON** | Mock data |
| **GitHub** | Version control |

---

## 📁 Folder Structure

PROJECT/
│── src/
│ ├── components/
│ │ ├── Sidebar.jsx
│ │ ├── TaskPanel.jsx
│ │ ├── TaskCard.jsx
│ ├── data/
│ │ └── mockData.json
│ ├── App.jsx
│ ├── main.jsx
│ └── index.css
│
│── assets/
│── index.html
│── package.json
│── tailwind.config.js
│── postcss.config.js
│── vite.config.js
│── .gitignore
│── README.md

yaml
Copy code

---

## 🧩 Assumptions

- Tasks are stored in memory using React state.
- When the page refreshes, data resets (no backend or database).
- Status values used:
  - `Pending`
  - `In Progress`
  - `Completed`
- Default employee selection is the first employee in the list.

---

## ⚙️ Setup Instructions (Run Locally)

### 1️⃣ Clone the repository

```bash`
git clone https://github.com/AnushaDivvela/Employee-Task-Tracker.git
cd Employee-Task-Tracker

# Install dependencies
npm install

# Start development server
npm run dev
The app will run at:

http://localhost:5173/
![Dashboard Screenshot](https://github.com/user-attachments/assets/651fe8dc-ca23-4560-8227-aba6a0d45b39)






