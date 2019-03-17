This application uses goodreads api to look for books by title, author or isbn code.

This project was bootstrapped with `create-react-app` and deployed live at https://prudential-assignment.herokuapp.com/

# Running the application locally

**Prerequisites:** You need to have node and npm installed.

**Required Environment Variables:**

`api_key` : Goodreads API Key you can get from [here](https://www.goodreads.com/api/keys).

To run the application locally in development mode:

**Clone the repo:**

https://github.com/raiswathi5/prudential-assignment.git

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

# Features In Current Version:

1. Search for books by name.
2. Displays upto 20 search results in bootstrap cards.
3. Displays only title, author and link to goodreads page.
4. See the description, rating and other details by clicking on individual result.

# Future Implementation:

Some of the things that can be implemented in the future are:

1. Ability to sign in with github so users can add their own reviews and ratings.
2. Cosmetic enhancements.
