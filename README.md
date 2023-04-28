# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full stack open course

Fork the repository to complete course exercises

## Commands

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server
`npm test` to run tests
`npm run eslint` to run eslint
`npm run build` to make a production build
`npm run start-prod` to run your production build

---

> The uses keyword tells the workflow to run a specific action. An action is a reusable piece of code, like a function. Actions can be defined in your repository in a separate file or you can use the ones available in public repositories.

> Here we're using a public action actions/checkout and we specify a version (@v3) to avoid potential breaking changes if the action gets updated. The checkoutaction does what the name implies: it checkouts the project source code from Git.

> To set up Node.js, actions/setup-node action can be used.

> the with keyword is used to give a "parameter" to the action
