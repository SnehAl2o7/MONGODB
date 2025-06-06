# 📘 MongoDB Learning Hub

**LEARNING THE NOSQL DATABASE** 
🧠 Learn by doing | 💻 Real-World Practice | ⚡ Developer-Focused

![MongoDB](https://img.shields.io/badge/MongoDB-Learning-green?style=flat-square&logo=mongodb)
![Level](https://img.shields.io/badge/Level-Beginner--to--Advanced-blueviolet?style=flat-square)
![Ubuntu](https://img.shields.io/badge/OS-Ubuntu%2022.04-informational?style=flat-square&logo=ubuntu)

---

## 📂 Repository Overview

```
mongodb-learning/
├── 01_Basics/             → Intro, shell, collections, basic CRUD
├── 02_QueryOperators/     → Filters, projections, comparison ops
├── 03_DataModeling/       → Schema design, embedded vs ref
├── 04_Aggregation/        → Pipeline operators, real-world examples
├── 05_PyMongo/            → MongoDB with Python
├── 06_Mongoose/           → MongoDB with Node.js
├── 07_BackupRestore/      → mongodump, mongorestore, bson files
├── 08_MiniProjects/       → Practice apps & real-life models
└── README.md
```

---

## 📌 Goals of This Repository

- ✅ Gain fluency in MongoDB shell & query language  
- ✅ Learn modern NoSQL schema design principles  
- ✅ Use MongoDB with Python (PyMongo) & Node.js (Mongoose)  
- ✅ Build and back up your own mini-projects  
- ✅ Prepare for interviews and real-world applications  

---

## 🚀 Quick Start

### 1️⃣ Install MongoDB on Ubuntu

```bash
sudo apt update
sudo apt install -y mongodb
sudo systemctl enable --now mongodb
```

Verify:
```bash
mongod --version
```

Or refer to 👉 [Official Installation Docs](https://www.mongodb.com/docs/manual/installation/)

---

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/mongodb-learning.git
cd mongodb-learning
```

---

## 📚 Learn by Doing

Each section has:

| 📂 Folder            | 🧠 What You'll Learn                     | ✅ Activities             |
|----------------------|------------------------------------------|---------------------------|
| `01_Basics`          | Intro, commands, `insert/find`          | Try CRUD in `mongosh`     |
| `03_DataModeling`    | Embedding vs referencing                | Design sample schemas     |
| `04_Aggregation`     | `$match`, `$group`, `$project`, `$sort` | Practice pipelines        |
| `05_PyMongo`         | MongoDB with Python                     | Connect & query via script|
| `08_MiniProjects`    | End-to-end practice                     | Design your own system    |

🎯 **Track your progress** with a `progress.md` in each folder.

---

## 🧪 First Challenge

Try this in `01_Basics/`:

```bash
mongosh
```

```js
use vanshDB

db.students.insertOne({
    name: "Vansh",
    course: "MongoDB Basics",
    enrolled: true,
    marks: [82, 90, 88]
})

db.students.find().pretty()
```

➡️ Log what you did in `task_log.md`  
➡️ Reflect on what each command did in `notes.md`

---

## 💻 Tools We Use

- 💾 MongoDB Shell (`mongosh`)
- 🧪 MongoDB Compass (Optional GUI)
- 🐍 PyMongo (Python Driver)
- 🟢 Mongoose (Node.js ODM)
- 🧰 Ubuntu Terminal & Bash

---

## 🔗 Recommended Resources

- [📘 MongoDB Manual](https://www.mongodb.com/docs/manual/)
- [🎓 MongoDB University](https://learn.mongodb.com/)
- [📊 MongoDB Cheat Sheet](https://github.com/mongodb/mongo/blob/master/docs/mongodb_cheatsheet.md)
- [📼 YouTube MongoDB Tutorials](https://www.youtube.com/results?search_query=mongodb+tutorial+for+beginners)

---

## 💡 Contribution Guide

Want to contribute?

1. Fork the repo  
2. Create a branch `feature/your-feature-name`  
3. Submit a pull request  
4. Open issues for discussions

---

## 👤 Author

**Vansh**  
*CSE Student | Backend & AI Enthusiast | Ubuntu Power User*

---

## ⭐ Final Word

MongoDB isn’t just about storing data — it’s about structuring it smartly for real-world scale and speed.

> 🚀 Start experimenting. Break things. Learn fast. Build even faster.

---

<p align="center">
  <b>Happy Hacking 💻 | Consistency is 🔑</b>
</p>

