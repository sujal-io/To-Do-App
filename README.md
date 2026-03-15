# To-Do List Web Application

A fully responsive **To-Do List Web Application** built using **Vanilla JavaScript, HTML5, and CSS3** that helps users efficiently organize and manage their daily tasks.

The application uses the browser’s **localStorage API** to persist tasks, ensuring that data remains saved even after refreshing or closing the browser.

The project also includes a **custom EventEmitter class**, enabling **event-driven communication between different modules** of the application. This design makes the codebase more structured, scalable, and easier to maintain.

The main goal of this project is to demonstrate how a clean and modular application architecture can be implemented using **core web technologies without external frameworks**.

---

# 🚀 Features

- Add new tasks to the to-do list  
- Mark tasks as **completed or pending**  
- Delete tasks from the list  
- **Persistent task storage** using the browser's `localStorage`  
- Custom **EventEmitter class implementation**  
- **Event-driven architecture** for better modularity  
- **Fully responsive design** for mobile and desktop devices  
- Clean and modern **user interface**

---

# 🛠️ Tech Stack

| Technology | Purpose |
|-----------|--------|
| **HTML5** | Structure of the web application |
| **CSS3** | Styling and responsive layout |
| **Vanilla JavaScript** | Application logic and interactivity |
| **localStorage API** | Persistent storage of tasks |

---

# 📂 Project Structure

```
todo-app/
│
├── index.html        # Main HTML structure
├── style.css         # Styling and responsive design
├── script.js         # Application logic
├── EventEmitter.js   # Custom event handling system
└── README.md         # Project documentation
```


# 💡 How It Works

1. Users can add tasks using the input field.
2. Each task is stored in **localStorage** to maintain persistence.
3. The **EventEmitter class** allows different parts of the application to communicate through events.
4. When a task is added, completed, or deleted, an event is emitted and the UI updates automatically.

This event-driven design improves **code organization and maintainability**.

---

# 📱 Responsive Design

The interface is designed to adapt to different screen sizes, providing a smooth experience on:

- Mobile devices
- Tablets
- Desktop screens

---

# 🎯 Learning Outcomes

Through this project, the following concepts were explored:

- DOM manipulation using **Vanilla JavaScript**
- Building an **event-driven architecture**
- Implementing **custom event handling with EventEmitter**
- Using **localStorage for client-side persistence**
- Creating a **responsive UI with CSS**

---

# 📌 Future Improvements

- Add **task editing functionality**
- Implement **task categories or tags**
- Add **drag-and-drop task reordering**
- Include **due dates and reminders**

---
