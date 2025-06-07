
# 🌟 Radient Reflection — A Minimal Blog CMS in PHP

**Radient Reflection** is a lightweight, dynamic blog platform built using core PHP, MySQL, and vanilla HTML/CSS/JS. Developed during the ICFAI University Hackathon, it provides secure user authentication, full blog management, and modular frontend/backend separation.

## 🚀 Features

- 🔐 User Authentication with session handling
- 📝 Create, edit, and delete blog posts
- 🗃️ Manage categories and users (admin)
- 📁 Modular structure for easy customization
- ⚡ Runs via PHP’s built-in server (`php -S localhost:8000`)

## 🧱 Project Structure

```
ALGORITHM_AVENGERS/
├── core/
│   └── config.php
├── public/
│   ├── css/
│   │   ├── login.css
│   │   └── style.css
│   └── js/
│       └── main.js
├── views/
│   ├── about.html
│   ├── blog.html
│   ├── dashboard.html
│   ├── post.html
│   ├── signin.html
│   ├── signup.html
│   └── ... (other pages for CRUD)
├── add-post.php
├── add-post-logic.php
├── createuser.php
├── delete-post.php
├── index.php
├── login.php
├── logout.php
├── signup.php
└── README.md
```

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Core PHP (no framework)
- **Database**: MySQL
- **Dev Server**: PHP's built-in server

## ⚙️ How to Run Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/radient-reflection.git
    cd radient-reflection
    ```

2. Start the server:
    ```bash
    php -S localhost:8000
    ```

3. Open [http://localhost:8000](http://localhost:8000) in your browser.

4. Configure database in `core/config.php` and import the required MySQL schema.

## 📷 Screenshots

_Add screenshots here of login, post creation, and dashboard UI._

## 📜 License

MIT License
