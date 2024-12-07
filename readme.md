# JS ToDo List App

A simple, responsive, and functional To-Do List application built with HTML, CSS, and JavaScript. The app allows users to add, complete, and delete tasks, with task data saved to `localStorage` for persistence.

---

## Features

- **Add Tasks:** Enter tasks in the input box and click the **Add** button to add them to the list.
- **Mark as Completed:** Click on a task to mark it as completed, which adds a strikethrough effect.
- **Delete Tasks:** Click the × icon to remove a task from the list.
- **Persistent Data:** Tasks are saved in the browser’s `localStorage`, so they persist even after refreshing the page.

---

## Demo

You can see the app in action here: [Live Demo](https://github.com/anwerashif/JS-ToDoList-App)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/anwerashif/JS-ToDoList-App.git
   ```
2. Navigate to the project directory:
   ```bash
   cd js-todo-list-app
   ```
3. Open `index.html` in your preferred browser:
   ```bash
   open index.html
   ```

---

## File Structure

```
js-todo-list-app/
├── index.html        # HTML structure of the app
├── style.css         # Styling of the app
├── script.js         # App functionality
└── img/             # Images used in the app
    ├── icon.png        # App icon
    ├── checked.png     # Checked icon for completed tasks
    └── unchecked.png   # Unchecked icon for pending tasks
```

---

## How It Works

1. **Adding Tasks:**
   - Enter text in the input box.
   - Click the **Add** button to append the task to the list.

2. **Marking Tasks as Completed:**
   - Clicking on a task toggles the `checked` class, which adds a strikethrough style.

3. **Deleting Tasks:**
   - Clicking the × icon removes the task from the list.

4. **Saving Data:**
   - The `saveData()` function saves the current state of the task list to `localStorage`.

5. **Loading Data:**
   - The `showData()` function retrieves saved tasks from `localStorage` and displays them on page load.

---

## Technologies Used

- **HTML5**: Markup structure.
- **CSS3**: Styling and responsiveness.
- **JavaScript**: Interactivity and functionality.

---

## Contributions

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

For any inquiries or suggestions, feel free to contact:

- **GitHub:** [anwerashif](https://github.com/anwerashif/)