# 🌟 Login & Registration System (HTML + JavaScript + Bootstrap 5)

A clean and simple **Login, Register, and Dashboard** system built using **pure HTML, CSS (Bootstrap 5)** and **JavaScript with LocalStorage**.

---

## 🚀 Live Demo  
👉 **https://labdemo80.github.io/Test_1/**

---

## 📂 Project Structure

Test_1/
│── index.html
│── register.html
│── dashboard.html
│── styles.css
│── script.js
│── assets/
└── README.md

yaml
Copy code

---

## ✨ Features

- ✅ User Registration  
- ✅ Login Validation  
- ✅ LocalStorage-based authentication  
- ✅ Dashboard access only after login  
- ✅ Logout system  
- ✅ Beautiful Bootstrap 5 UI  
- ✅ Fully frontend (no backend needed)

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3 / Bootstrap 5**
- **JavaScript**
- **GitHub Pages (Hosting)**

---

## 📘 How to Run Locally

git clone https://github.com/labdemo80/Test_1.git
cd Test_1

arduino
Copy code

Then open:

index.html

yaml
Copy code

in your browser.

---

## 🌐 Deploying Using GitHub Pages

1. Go to **Settings**
2. Open **Pages**
3. Under **Build & Deployment**, choose:
Branch: main
Folder: /root

yaml
Copy code
4. Click **Save**

Your website will go live in **30–60 seconds**.

---

## 🔐 Authentication Flow

### 1. Registration
User details stored in LocalStorage:
localStorage.setItem("user", JSON.stringify({ ... }));

shell
Copy code

### 2. Login
Checks stored email & password.

### 3. Dashboard Protection
if (localStorage.getItem("isLoggedIn") !== "true") {
window.location.href = "index.html";
}

shell
Copy code

### 4. Logout
localStorage.removeItem("isLoggedIn");

yaml
Copy code

---

## 🧩 Future Enhancements

- 🔒 Add password encryption  
- 👥 Multi-user system  
- 🔗 Backend integration (Node.js / Firebase)  
- 🎨 Better UI animations  
- 🌙 Dark mode  

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## ⭐ Support

If you find this project useful, don’t forget to **⭐ star the repository**!
