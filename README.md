# Todo Redux Toolkit React App

This is a simple Todo List application built using React.js and Redux Toolkit. It allows users to add new todos, mark todos as completed, and delete todos from the list.

## Features

1. Add new todos: Users can input new todos into the input field and press "Add Todo" to add them to the list.
2. Remove todos: Each todo item has a delete button that allows users to remove todos from the list.
3. Todo completion: Todos can be marked as completed by clicking on them. Completed todos will have a strike-through style applied.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine:

git clone https://github.com/hareshvegad/Todo-Redux-Toolkit-React-App.git

2. Navigate to the project directory:

cd todo_redux_toolkit

3. Install dependencies:

npm install

4. Run the development server:

npm start

5. Open your browser and navigate to http://localhost:3000 to view the application.

## Project Structure

The project structure is as follows:

    src/
        App.js: Main component that renders the AddTodos and Todos components.
        AddTodos.js: Component responsible for adding new todos.
        Todos.js: Component that displays the list of todos and handles todo deletion.
        app/
            Store.js: Redux store configuration using Redux Toolkit's configureStore function.
        features/
            todo/
                TodoSlice.js: Redux slice containing todo state and reducers for adding and removing todos.

## Technologies Used

1. React.js: A JavaScript library for building user interfaces.
2. Redux Toolkit: An official, opinionated, batteries-included toolset for efficient Redux development.
3. React-Redux: Official Redux bindings for React.
4. nanoid: A tiny, secure, URL-friendly unique string ID generator.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.