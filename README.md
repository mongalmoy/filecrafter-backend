# 📁 FileCrafter Backend

**FileCrafter** is a lightweight Node.js + Express backend service that dynamically creates a user-defined folder structure and provides it as a downloadable `.zip` file. It is built to serve as the backend engine for a web-based folder generator tool.

---

## 🚀 Features

- Accepts user input for folder/file structure
- Dynamically creates the folder structure in the server's temp directory
- Compresses the structure into a `.zip` file
- Sends the `.zip` file as a downloadable response
- Clean separation of routes, controllers, and utilities

---

## 🧱 Tech Stack

| Layer        | Technology         |
| ------------ | ------------------ |
| Backend      | Node.js + Express  |
| File System  | Node `fs`, `path`  |
| Compression  | `archiver` npm lib |
| Cross-Origin | `cors`             |
| Config       | `dotenv`           |

---

## 🗂️ Project Structure

filecrafter-backend/
├── controllers/
│ └── folderController.js
├── routes/
│ └── folderRoutes.js
├── utils/
│ └── folderBuilder.js
├── temp/ # Generated folders stored temporarily
├── .env
├── .gitignore
├── app.js
├── package.json
└── README.md

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/filecrafter-backend.git
cd filecrafter-backend
```
