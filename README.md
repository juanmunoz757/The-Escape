# The Escape


A fun and interactive web application that generates mazes using the Depth-First Search (DFS) algorithm and solves them using Breadth-First Search (BFS). Users can navigate the maze manually, customize themes, and select unique icons for the player, start, and end points. The application is fully responsive, adapting to various screen sizes.

## ✨ Features

* **Dynamic Maze Generation:** Generates unique mazes of user-defined dimensions using the efficient Depth-First Search algorithm.

* **Automated Maze Solver:** Finds the shortest path from start to end using the Breadth-First Search algorithm.

* **Interactive Player Movement:** Control the player character through the maze using arrow keys or on-screen buttons.

* **Undo/Redo Functionality:** Easily backtrack and redo player moves with dedicated controls.

* **Customizable Themes:** Choose from a variety of vibrant gradient themes that dynamically change the maze and UI colors.

* **Customizable Icons:** Select distinct Font Awesome icons for the player, maze start, and maze end points.

* **Responsive Design:** The maze and controls adapt seamlessly to different screen sizes, including mobile devices.

* **Clear Path Option:** Reset your manual path to start fresh at any time.

## 🚀 How to Play

1. **Generate a New Maze:** Adjust the "Width" and "Height" values to set your desired maze dimensions (5x5 to 100x100). Click the "New Maze" button.

2. **Navigate the Maze:**

   * Use the **Arrow Keys** (Up, Down, Left, Right) on your keyboard.

   * Use the **on-screen Up, Down, Left, Right buttons** for touch devices or mouse control.

3. **Solve the Maze:** Click the "Solve Maze" button to see the shortest path from start to end. This will reset your current path.

4. **Clear Your Path:** If you're stuck or want to restart your manual attempt, click "Clear Path" to move the player back to the start.

5. **Undo/Redo Moves:** Use "Undo" to reverse your last move, and "Redo" to re-apply an undone move.

6. **Customize:**

   * Use the "Theme" dropdown to change the visual gradient theme of the application.

   * Use the "Player Icon," "Start Icon," and "End Icon" dropdowns to personalize the maze elements.

## 💻 Technologies Used

* **HTML5:** Structure of the web page.

* **CSS3:** Styling, including responsive design and dynamic gradient themes.

* **JavaScript (ES6+):** Core logic for maze generation (DFS), maze solving (BFS), player movement, and UI interactivity.

* **HTML Canvas API:** For drawing the maze walls and paths.

* **Font Awesome:** Provides a wide range of customizable icons.

## 🛠️ Setup (Local Development)

This is a client-side only application. You can simply download the `index.html` file and open it in any modern web browser.

1. **Clone the repository (if applicable):**



    ```
    git clone [https://github.com/Boda1607/maze-generator-solver.git](https://github.com/Boda1607/maze-generator-solver.git)
    cd maze-generator-solver
    ```


2. **Open `index.html`:** Double-click the `index.html` file or drag it into your web browser.

## 🌐 Demo

You can see a live demo of the application here: [https://thescape.netlify.app/](https://thescape.netlify.app/)

## 💖 Credits

Made with ❤️ by [AbdElRahman](https://abdelrahmanz.netlify.app/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
