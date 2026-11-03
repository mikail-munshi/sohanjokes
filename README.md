# Sohan Roast API

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/License-MIT-800000?style=for-the-badge&logo=opensourceinitiative&logoColor=white" />
</p>

A lightweight, humorous, and fully customizable Node.js & Express REST API that serves up **200 custom-crafted dark/roast jokes** specifically targeting your friend **Sohan**. Built for fun, testing, and API integration practice!

---

## 🛠️ Tech Stack

* **Runtime:** [Node.js](https://nodejs.org/)
* **Framework:** [Express.js](https://expressjs.com/)
* **Language:** JavaScript (ES6+)

---

## 📁 Project Structure

```text
sohan-roast-api/
│
├── index.js          # Main server file & joke database
├── package.json      # Project dependencies and metadata
└── README.md         # Project documentation
```
---

## 💻 How to Use the API

You can test and use this API in a few different ways:

### 1. Via Web Browser
Open your browser and visit:
* To get a random joke: `http://localhost:3000/api/jokes/random`
* To view all jokes: `http://localhost:3000/api/jokes`

### 2. Via Terminal (`curl`)
Run this command in your terminal while the server is running:
```bash command
curl http://localhost:3000/api/jokes/random
```


