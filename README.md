# 📚 Bookoria - Ecommerce Bookstore

An online platform for browsing, purchasing, and reviewing books. This full-stack web application allows users to explore a wide variety of books, add them to a cart, and securely checkout.

![UserAdmin](https://github.com/user-attachments/assets/a0202187-a329-41d6-950c-68f5654b8183)



---

## 📦 Features

- 🛒 User-friendly shopping cart
- 💳 Secure checkout process
- 📚 Admin dashboard for managing books, orders, and users


---

## 🛠️ Tech Stack

**Frontend:**  
- React.js
- HTML5 / CSS3 / JavaScript  
- Tailwind

**Backend:**  
- Node.js + Express.js   
- MongoDB

**Authentication:**  
- JWT-based user login and registration

---

## 🎯 Special Feature – Discount Quiz

To engage users and reward curious readers, this bookstore offers an **Interactive quiz** where customers can earn a **discount coupon** based on their score.

### 🧠 How It Works:

- Customers are invited to take a short quiz.
- Questions are multiple-choice and curated by the admin.
- If the user passes they receive a **one-time discount code**.
- The code can be applied during checkout for a reduced price on their current purchase.
- Each user can attempt the quiz **only once**.

### 👨‍💼 Admin Capabilities:

- Create, update, or delete quiz questions through the admin dashboard.
- Set difficulty level.

### 🔐 Rules:

- One attempt per user (until next quiz added by user).
- Questions are randomized per attempt.

This feature encourages engagement, builds brand loyalty, and offers a fun twist to regular shopping!



## 📥 Installation

```bash
# Clone the repository
git clone https://github.com/MSN033/e-book.git

# Navigate into the project directory
cd e-book

# Install dependencies (for both frontend & backend if needed)
npm install

# Run the development server
npm start
