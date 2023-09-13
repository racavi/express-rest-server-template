# express-server-template
This repository provides a NodeJS Express server template

## Prerequisites

This is a Node.js® application, as such, you will need to have Node.js installed in your machine to be able to run this application.

## Getting started

### Install the dependencies

To be able to run this application, you will need to install its dependencies. To do so you will have to:

1. Navigate into application source directory

2. Install required Node node modules

The following commands will reproduce these steps within a terminal:

```lang-bash
cd app/
npm install
```

### Configure environment variables

This app uses a module named `dotenv` to manage environment variables. Loading environment variables from a `.env` file into the [Node process.env API](https://nodejs.org/docs/latest/api/process.html#process_process_env). 

To test it, create the file `app/.env` and declare the `PORT` environment variable with a value of your choice, e.g: `3000` do this by pasting the following content to the file:

```lang-makefile
PORT=3000
```

### Run the application

You can run the application by issuing the following command:

```lang-bash
node app.js
```

After that, open your web browser of choice and load http://localhost:3000/ to see the output. 

## References

- [dotenv](https://www.npmjs.com/package/dotenv)
- [Express](https://www.npmjs.com/package/express)
- [Node.js](https://nodejs.org/)
