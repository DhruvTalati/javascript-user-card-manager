# JavaScript User Card Manager

A simple **User Management Web App** built using **Vanilla JavaScript and Tailwind CSS**.

This project allows users to add and manage user profiles dynamically using DOM manipulation.  
It was built while learning **Advanced JavaScript concepts like `this`, `bind`, and object-based architecture**.

---
## Live Demo

https://javascript-user-card-manager.vercel.app/
---

## 🚀 Features

- Add new users using a form
- Display users as profile cards
- Remove users dynamically
- Clean responsive UI using Tailwind CSS
- Object-oriented structure using a `userManager` object
- Uses advanced JavaScript concepts like:
  - `this`
  - `bind()`
  - Event handling
  - DOM manipulation

---

## 🛠️ Tech Stack

- **HTML5**
- **Tailwind CSS**
- **Vanilla JavaScript (ES6)**

---

## 📂 Project Structure

```
project-folder
│
├── index.html
├── script.js
└── README.md
```

---

## 📸 Application Preview

Users can:

1. Enter their **Name**
2. Enter their **Role / Roll**
3. Write a **short Bio**
4. Provide a **Photo URL**

After submitting the form, the user profile appears as a **card below the form**.

Each card includes:

- Profile Photo
- Name
- Role
- Bio
- Remove Button

---

## ⚙️ How It Works

The application is controlled using a JavaScript object called `userManager`.

It manages:

- Form submission
- User storage
- Rendering UI
- Removing users

Example structure:

```javascript
const userManager = {
  users: [],
  init(){},
  addUser(){},
  renderUi(){},
  removeUser(){}
}
```

Users are stored inside the `users` array and the UI updates dynamically whenever a new user is added or removed.

---

## ▶️ Running the Project

1. Clone the repository

```
git clone https://github.com/your-username/javascript-user-card-manager.git
```

2. Open the folder

```
cd javascript-user-card-manager
```

3. Run the project

Simply open **index.html** in your browser.

---

## 📚 Concepts Learned

This project helped practice:

- DOM Manipulation
- Event Handling
- `this` keyword
- `bind()` method
- Dynamic UI rendering
- Array manipulation
- JavaScript object architecture

---

## 🎯 Future Improvements

Possible enhancements:

- Edit user profiles
- LocalStorage support
- Toast notifications
- Image fallback handling
- Animations for card creation
- User validation improvements

---

## 👨‍💻 Author

**Dhruv Talati**

---

## ⭐ Support

If you like this project, consider giving it a **star ⭐ on GitHub**.
