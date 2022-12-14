# tweaks-app

A study of designing and engineering a three-tier, but otherwise flat app configuration API using GUI elements and injectable, inferrable values.

## Setup

### Installation

1. Run NPM installation.

   ```sh
   npm i
   ```

2. (optional) Install the `./server` dependencies manually. Without modifications to this repository, this step is already handled for you in step 1.

   ```sh
   cd server
   npm i
   ```

### Environment

1. Create a copy of `.env.example` to `.env.local`.

   ```sh
   cp .env.example .env.local
   ```

2. Modify your `REACT_APP_API_BASE_URL` to match the `./server` port number, especially if you've changed the port number there.

   ```properties
   REACT_APP_API_BASE_URL=http://localhost:<port number>`
   ```

## Usage

1. Run the REST API server in a terminal.
   ```sh
   npm run serve
   ```

2. Run the GUI app client in another terminal.
   ```sh
   npm start
   ```

----

## JSON Server notes

This project comes with the a subproject bootstrapped with instructions from [JSON Server](https://github.com/typicode/json-server#getting-started).

## Available Scripts

### `npm run serve`

Aliases over [the `json-server` command](https://github.com/typicode/json-server#cli-usage) with a local DB.json and port 4000.

Open [http://localhost:4000](http://localhost:4000) to view it in the browser.

----

## Create React App notes

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can???t go back!**

If you aren???t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you???re on your own.

You don???t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn???t feel obligated to use this feature. However we understand that this tool wouldn???t be useful if you couldn???t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
