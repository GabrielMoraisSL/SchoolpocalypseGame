# Schoolpocalypse
Schoolpocalypse is an action-survival game set inside a college on the brink of chaos. After releasing the grades for the latest exam, a professor becomes the main target of a student uprising. Outraged by the results, the students arm themselves with whatever they can find — books, pencils, and even laptops — and embark on a relentless chase through the campus hallways.

Without understanding how things spiraled out of control so quickly, the professor embarks on a desperate escape, crossing various college environments — classrooms, courtyards, laboratories, and the parking lot. Dodging projectiles thrown by the enraged students, he remains determined in his mission: to reach the server room and format the system to erase all grades and, hopefully, restore order.

But the real twist comes after formatting: even with all records erased, the professor decides to retake the exam — reigniting the flames of rebellion and starting a new cycle of chaos.

Developed by third-semester Software Engineering students, Schoolpocalypse is a fast-paced satire of academic life, where exams can be deadly and the only way out is to run... or to format.

-----

## Technologies Used

  - **Node.js**
  - **Vue.js**
  - **Vite** (for a faster development environment)

-----

## Project Structure

```
 📂src/
   📂components/
     📂buttons/
       📄ButtonCompletes.jsx
       📄ButtonTasks.jsx
     📂input/
       📄Input.jsx
     📂state/
       📄store.js
     📂title/
       📄Title.jsx
     📄AddTasks.jsx
     📄Completes.jsx
     📄Tasks.jsx
   📂pages/
     📄TaskPage.jsx
   📄App.css
   📄App.jsx
   📄index.css
   📄main.jsx
```

-----

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

1.  **Visual Studio Code** (recommended code editor) `https://code.visualstudio.com`
2.  **Node.js** `https://nodejs.org/`
3.  **Git** `https://git-scm.com/downloads`

-----

## How to Install and Run

Open Visual Studio Code, then press `Ctrl + J` and follow the instructions in your terminal:

1.  Clone this repository:

    ```bash
    git clone https://github.com/GabrielMoraisSL/ToDoList-Projeto.git
    ```

2.  Access the project directory:

    ```bash
    cd ToDoList-Projeto
    ```

3.  Install dependencies:

    ```bash
    npm install
    ```

4.  Run the project:

    ```bash
    npm run dev
    ```

The project will be available at `http://localhost:5173/` (Vite's default port).

-----

## Code Structure

### Main Components

### Structural Components

These components complement the main ones for their functionality, such as:

  - `ButtonCompletes.jsx` and `ButtonTasks.jsx`: Manage button functionality.
  - `Input.jsx`: Manages input functionality.
  - `store.js`: Specific to Zustand, it creates a hook that manages the global state of the application. It defines functions to add, delete, and move tasks between lists, ensuring the state is updated correctly.
  - `Title.jsx`: Manages title functionality.

-----

## Features

  - **Add Task**: Users can add a new task by providing a title and description.
  - **Move Task to Completed**: Users can move a task to the completed tasks list.
  - **Move Task to Pending**: Users can move a completed task back to the pending tasks list.
  - **Delete Task**: Users can delete tasks from both the pending and completed lists.
  - **View Description**: Users can view the task description from both the pending and completed lists.

-----

## License

This project is licensed under the [MIT License](https://www.google.com/search?q=LICENSE).

-----

## Contributions

Contributions are welcome\! To contribute:

1.  Fork the repository.
2.  Create a new branch for your feature (`git checkout -b my-feature`).
3.  Commit your changes (`git commit -m 'Adds new feature'`).
4.  Push to the branch (`git push origin my-feature`).
5.  Open a Pull Request.

-----
