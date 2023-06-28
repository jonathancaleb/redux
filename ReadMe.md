# Employee Management CRUD App

This is a simple CRUD (Create, Read, Update, Delete) application built with React.js and Redux. The app allows you to manage employee data and store it locally using JSON as the database format.

## Features

- Create new employees by providing their details such as name, designation, and salary.
- Read and display a list of all employees in a table format.
- Update employee information, such as name, designation, and salary.
- Delete employees from the database.
- Store employee data locally using JSON format as the database.

## Technologies Used

- React.js: A JavaScript library for building user interfaces.
- Redux: A state management library for JavaScript applications.
- Local Storage: A web API used to store data in the browser's local storage.
- JSON: A lightweight data-interchange format used for storing and transmitting data.

## Getting Started

To run the application locally on your machine, follow these steps:

1. Clone this repository to your local machine.

```
git clone https://github.com/your-username/employee-management-app.git
```

2. Navigate to the project directory.

```
cd employee-management-app
```

3. Install the dependencies using npm or yarn.

```
npm install
```
or
```
yarn install
```

4. Start the development server.

```
npm start
```
or
```
yarn start
```

5. Open your browser and visit `http://localhost:3000` to see the application running.

## Folder Structure

The folder structure of the project is organized as follows:

- **`src`**: Contains the source code of the application.
  - **`actions`**: Defines Redux actions for employee management.
  - **`components`**: Contains reusable components used in the application.
  - **`reducers`**: Implements Redux reducers for managing employee data.
  - **`utils`**: Includes utility functions for interacting with local storage.
  - **`App.js`**: The main entry point of the application.
  - **`index.js`**: Renders the application in the browser.
- **`public`**: Contains the static assets and HTML template for the application.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Ensure that you follow the code style and conventions used in the project.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This application was created as a sample project to demonstrate the usage of React.js, Redux, and local storage for storing employee data. It serves as a starting point for building more complex applications or learning the basics of the mentioned technologies.