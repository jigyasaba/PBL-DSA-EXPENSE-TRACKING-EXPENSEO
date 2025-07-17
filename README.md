# Expenseo – Your Budget Buddy

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)


**Team Project**:


---

## 📋 Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technology Stack](#technology-stack)
4. [Data Structures & Algorithms](#data-structures--algorithms)
5. [Architecture & Workflow](#architecture--workflow)
6. [Installation & Setup](#installation--setup)
7. [Usage & Walkthrough](#usage--walkthrough)
8. [Sync & Monthly Reports](#sync--monthly-reports)
9. [Team Responsibilities](#team-responsibilities)
10. [Contributing](#contributing)
11. [License](#license)

---

## 🔍 Project Overview

Expenseo is a DSA‑driven personal expense tracker implemented as a static web app (HTML/CSS/JS) with an optional GTK desktop front‑end in C. It empowers users to:

* **Record & Manage**: Add, edit, delete, and undo expense entries.
* **Categorize & Limit**: Assign categories and set monthly budget thresholds.
* **Bill Splitting**: Use a greedy algorithm to minimize friend‐settlement transactions.
* **Analytics**: Interactive charts (pie, trend) for spending insights.
* **OCR Entry**: Scan bills/images via Tesseract.js.

Expenseo demonstrates practical data structures (arrays, stacks, maps) and algorithms (sorting, greedy) in a user‑centric financial tool.

---

## ✨ Features

* **User Authentication** (web)
* **Undo/Redo**: Custom LIFO stack for reversible actions
* **Category Alerts**: Real‑time warnings on budget exceedance
* **Greedy Split**: Minimal transactions for multi‑user bill split
* **Visual Charts**: Chart.js (web) or Cairo/GTK (desktop)
* **OCR Integration**: Auto‑populate via Tesseract.js
* **LocalStorage**: Persistent browser storage

---

## 🛠️ Technology Stack

| Layer                | Tools / Libraries                   |
| -------------------- | ----------------------------------- |
| **Frontend (Web)**   | HTML, CSS, JavaScript, Tailwind CSS |
| **Charts**           | Chart.js                            |
| **OCR**              | Tesseract.js                        |
| **Storage (Web)**    | localStorage (JSON)                 |           
| **Deploy**           | GitHub Pages /      |

---

## 📚 Data Structures & Algorithms

* **Arrays**: Dynamic storage of expense records
* **Stacks**: Undo/Redo mechanism
* **Hash Maps**: Category/date aggregations
* **Quick Sort**: Chronological sorting
* **Greedy Algorithm**: Optimal bill splitting
* **Binary Search**: Efficient filtering

---

## 🏗️ Architecture & Workflow

1. **Frontend**: Collects expenses → stores in `localStorage`.
2. **OCR Module**: Parses bill images via Tesseract.js.
---

## 🚀 Installation & Setup

1. **Clone Repo**

   ```bash
   git clone https://github.com/<your-username>/expenseo.git
   cd expenseo
   ```
2. **Web App**:

   * Open `index.html` in a browser or deploy to GitHub Pages:

     ```bash
     git push origin main
     ```
   

---

## 🎬 Usage & Walkthrough

1. **Launch**: Open `index.html`
2. **Add Expense**: Enter details → click **Add**.
3. **Undo/Delete**: Use **Undo** to revert.
4. **Set Limits**: Configure under **Settings**.
5. **View Charts**: Click **Analytics**.
6. **OCR Entry**: **Upload** bill image → form auto‑fills.
7. **Split Bills**: Navigate to **Split Bill**, enter names/amounts, click **Divide**.
8. **Export/Email**: **Export CSV** or click **Send Report**.
   --------
# Expenseo – Your Budget Buddy

[![GitHub Pages](https://img.shields.io/badge/Pages-Deployed-blue.svg)](https://jigyasaba.github.io/expenseo/)

🔗 **Live Site**: [https://jigyasaba.github.io/expenseo/](https://jigyasaba.github.io/expenseo/)

---


## 🤝 Contributing

1. Fork the repo
2. Create branch: `git checkout -b feat/YourFeature`
3. Commit changes: `git commit -m "Add YourFeature"`
4. Push: `git push origin feat/YourFeature`
5. Open a Pull Request

Please follow code style and include tests for new features.

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
