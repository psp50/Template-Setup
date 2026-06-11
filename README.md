# Project Setup Tool

A simple Node.js CLI tool that automatically creates a basic web project structure with an Express server.

## Features

- Creates a new project folder
- Generates starter HTML, CSS, and JavaScript files
- Creates an Express.js server
- Generates a `package.json`
- Creates a `.gitignore`
- Automatically installs dependencies

---

## Project Structure

```text
project-name/
│
├── src/
│   ├── index.html
│   ├── style.css
│   └── main.js
│
├── server.js
├── package.json
├── .gitignore
└── node_modules/
```

---


## Usage

Run the script and provide a project name:

```bash
node index.js myWebProject
```

Example:

```bash
node index.js portfolio-site
```

If no project name is provided, the default name will be:

```bash
myWebProject
```

---
## Starting the Generated Project

Navigate into the generated project:

```bash
cd portfolio-site
```

Start the server:

```bash
npm start
```

Open:

```text
http://localhost:3000
```

---

## Example Output

```bash
Created project folder: portfolio-site
Created: src/index.html
Created: src/style.css
Created: src/main.js
Created: server.js
Created: package.json
Created: .gitignore

Installing dependencies...

Dependencies installed successfully.

Project setup completed!
```

---

## Dependencies

- Express.js
