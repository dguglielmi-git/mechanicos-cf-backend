
# MechanicOS - WebApp Car Workshop Manager

Google Cloud Functions Backend Server

## Getting Started 🚀

First of all, you need to install `firebase-tools` if you want to work with firebase from the CLI.

### Installing firebase-tools
```sh
> npm install -g firebase-tools
```


### How to create a project for Google Cloud Functions 🔧

Below you will find the steps to create a project using firebase-tools CLI.


```sh
> firebase init
```


```sh
> Functions: Configure and deploy Cloud Functions

Options: Create a new project
Please specify a unique project id (warning: cannot be modified afterward)[6-30 characters]: 
> frb-gql-your-project

What whould you like to call your project? (default to your project ID)
> <Press Enter>

What language would you like to use to write Cloud Functions?
> Javascript

Do you want to use ESLint to catch probable bugs and enforce style?
> No

Do you want to install dependencies wityh npm now?
> Yes

```

## Test and Deploy 📦

Before deploying your functions, you can test if everything is running properly in your local machine:

### Running in your local machine for testing purposes
```sh
> firebase serve
```

### Deploy your function in Firebase
```sh
> firebase deploy
```


## Built with 🛠️

* [Mongoose ](https://www.npmjs.com/package//mongoose) - Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment. Mongoose supports both promises and callbacks.
* [Firebase ](https://www.npmjs.com/package/firebase-tools) - The Firebase Command Line Interface (CLI) Tools can be used to test, manage, and deploy your Firebase project from the command line.
* [GraphQL Apollo Server ](https://www.npmjs.com/package/apollo-server) - Apollo Server is a community-maintained open-source GraphQL server. It works with many Node.js HTTP server frameworks, or can run on its own with a built-in Express server. Apollo Server works with any GraphQL schema built with GraphQL.js--or define a schema's type definitions using schema definition language (SDL).
* [JWT ](https://www.npmjs.com/package/jwt) - A slight adaptation of jwt-js for Node.
* [mongoose-float ](https://www.npmjs.com/package/mongoose-float) - This library can solve one well known problem with JavaScript Number arithmetic imprecise, when, for example, 3.3 * 3 becomes 9.899999999999999, ugly. This can occur when you try to save double values in Mongo DB, it can be balance, discounts etc.
* [dotEnv ](https://www.npmjs.com/package/dotenv) - Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env. Storing configuration in the environment separate from code is based on The Twelve-Factor App methodology.

## Version 📌

We used [SemVer](http://semver.org/) for versioning. Check out the whole version list available [tagsRepo](https://github.com/dguglielmi-git/mechanicos-cf-backend/tags).

## Author ✒️

* **Daniel Guglielmi** - Software Engineer - [dguglielmi-git](https://github.com/dguglielmi-git)


## License 📄

There is no license available.

## Thanks 🎁

Thanks for using this project.


---
⌨️ with ❤️ by [dguglielmi-git](https://github.com/dguglielmi-git) 😊