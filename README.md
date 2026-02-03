# 🛒 Dynamic Shopping List
## 🚀 Live Demo
[View the Live Project here](https://luismiguelmiranda92.github.io/shopping-list-project/)

A lightweight, interactive web application built with **Vanilla JavaScript**, HTML5, and CSS3. This project demonstrates DOM manipulation, event handling, and dynamic element creation—fundamental skills for modern web development.



## 🚀 Features

- **Dynamic Addition:** Add items to your list instantly without refreshing the page.
- **Interactive Deletion:** Each item comes with its own "Delete" button for surgical removal from the list.
- **User Experience:** Automatic input focusing for a faster, smoother workflow.
- **Clean Architecture:** Uses JavaScript closures to manage the scope of dynamically created elements.

## 🛠️ Technical Breakdown

This project was a deep dive into the **Document Object Model (DOM)**. Key concepts explored include:

* **`document.createElement()`**: Generating nodes on the fly.
* **`Node.appendChild()`**: Building the parent-child relationship between `<li>`, `<span>`, and `<button>`.
* **Event Listeners**: Capturing user clicks and preventing default form submissions using `event.preventDefault()`.
* **Closures**: Nesting the delete logic inside the creation function to ensure each button "remembers" its parent element.

## 📂 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/LuisMiguelMiranda92/shopping-list-project.git](https://github.com/LuisMiguelMiranda92/shopping-list-project.git)
