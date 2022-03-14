# todApp-Next

# Introduction

This is a basic CRUD application built on nest.js & MongoDB as backend. Here I have used **TypeScript** for writing the code.
## Installation
If you want to use it , download the folder & do **npm i** for installation.

```bash
npm i
```
**To start the server use following command, & sertver runs at 3000.**
```
npm start
```

## Endpoints Usage

To fetch all todos in database.

**GET**
```
http://localhost:3000/todo
```

To create a todo, pass the data as JSON format in the body.

**POST**
```
http://localhost:3000/todo
```

To update the todo

**PUT**
```
http://localhost:3000/todo/<id>
```

To delete the todo.

**DELETE**
```
http://localhost:3000/todo/<id>
```
