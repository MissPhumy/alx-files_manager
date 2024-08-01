# 0x04. Files Manager

## Description
This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination, and background processing. The objective is to build a simple platform to upload and view files, which includes user authentication via a token, listing all files, uploading new files, changing the permission of a file, viewing a file, and generating thumbnails for images.

## Features
- **User Authentication**: Authenticate users via a token.
- **File Management**:
  - List all files.
  - Upload a new file.
  - Change permission of a file.
  - View a file.
  - Generate thumbnails for images.

You will be guided step by step for building it, but you have some freedoms of implementation, such as splitting the code into more files (the `utils` folder will be your friend).

This kind of service already exists in real life, but this project serves a learning purpose to assemble each piece and build a full product.

Enjoy!

## Resources
Read or watch:
- [Node JS getting started](https://nodejs.org/en/docs/guides/getting-started-guide/)
- [Process API doc](https://nodejs.org/api/process.html)
- [Express getting started](https://expressjs.com/en/starter/installing.html)
- [Mocha documentation](https://mochajs.org/)
- [Nodemon documentation](https://nodemon.io/)
- [MongoDB](https://www.mongodb.com/)
- [Bull](https://github.com/OptimalBits/bull)
- [Image thumbnail](https://www.npmjs.com/package/image-thumbnail)
- [Mime-Types](https://www.npmjs.com/package/mime-types)
- [Redis](https://redis.io/)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
- How to create an API with Express
- How to authenticate a user
- How to store data in MongoDB
- How to store temporary data in Redis
- How to set up and use a background worker

## Requirements

### General
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using node (version 12.x.x)
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should use the `.js` extension
- Your code will be verified against lint using ESLint

### Provided Files
- `package.json`
- `.eslintrc.js`
- `babel.config.js`

Don't forget to run `$ npm install` when you have the `package.json`.
