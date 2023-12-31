# https://todo-app-manager-eight.vercel.app/

# Todo List Manager

The Todo List Manager is a simple web application built with React that allows users to create, manage, and track their tasks in a to-do list. Users can add new tasks, mark tasks as completed, and remove tasks from the list. It also includes input validation for task titles using a schema to ensure data integrity.

## Features

- Add tasks to the to-do list.
- Mark tasks as "pending" or "completed."
- Remove tasks from the list.
- Input validation for task titles.
- Dynamic error handling for invalid inputs.

## Technologies Used

- React: The JavaScript library for building user interfaces.
- [Yup](https://github.com/jquense/yup): A schema validation library used for input validation.
- HTML and CSS: The structure and styling of the web page.

## How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/todo-list-manager.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm start
   ```

4. Open your web browser and visit `http://localhost:3000` to access the Todo List Manager.

5. Use the application to add, update, and remove tasks from your to-do list.

## Code Structure

The code is organized into two main components:

1. **Sec Component (Todo List Manager)**: This component handles the overall structure of the application, manages the state, and includes the logic for adding, updating, and removing tasks. It also handles input validation and error handling.

2. **First Component (Individual Task)**: This component represents an individual task within the to-do list. It receives data from the Sec component, such as task title and status, and provides buttons to update the task's status and remove the task from the list.


Please customize this README according to your specific project details and provide any additional information that might be relevant.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
