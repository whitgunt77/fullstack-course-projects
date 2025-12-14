# Full Stack Course Projects

This repository contains multiple React applications built as part of the **Full Stack Open** course  assignments.
Each project is located in its own subdirectory and can be run independently.

---

## 📁 Project Structure

fullstack-course-projects/

      ├─ unicafe/
      
      ├─ anecdotes/
      
      └─ README.md

Each subdirectory contains a complete **Vite + React** application with its own dependencies.

---

## 🧪 Projects

### ⅰ Unicafe

A feedback application for the University of Helsinki cafeteria.

**Features:**
- Users can give feedback: **good**, **neutral**, **bad**
- Displays statistics:
    - total feedback count
    - average score
    - percentage of positive feedback
- Statistics are shown in a table
- Displays a message if no feedback has been given

**Location:**
/unicafe

**Run the project:**
```bash
cd unicafe
npm install
npm run dev
```

### ⅱ Anecdotes

An application that displays software development anecdotes.

**Features:**
- Displays a random anecdote
- Users can vote for anecdotes
- Tracks votes for each anecdote
- Displays the anecdote with the most votes

**Location:**
/anecdotes

**Run the project:**
```bash
cd anecdotes
npm install
npm run dev
```

## 🖥 Technologies Used
- React
- Vite
- JavaScript (ES6+)
- npm

## ✍🏼 Notes
- Each project is **self-contained**
- Projects only store data for the current browser session
