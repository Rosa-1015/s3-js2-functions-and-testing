# Java Script methods & Unit Tests 

## 🎬 Description

A company in the audiovisual sector requested a web application to help their employees quickly find movies from a large internal database, as the process was previously done manually.
During this sprint, the application's core was developed, implementing the full logic for filtering and sorting movies, with all functionality verified through Jest tests.

## 📁 Project Structure

```plaintext
starter-code-frontend-sprint-3-movies/
│
├── node_modules/
├── src/
│   ├── data.js          # Movies dataset (array of objects)
│   ├── films.js         # Logic implementation goes here
│   └── index.html
│
├── tests/
│   └── films.spec.js    # All unit tests
│
├── test-results.html    # Visual test results (generated)
├── .gitignore
├── package.json
├── package-lock.json
├── README.md
```

## 📋 Requirements

### 1. Clone the repo

```bash

git clone https://github.com/Rosa-1015/s3-js2-functions-and-testing

```

### 2. Disconnect from Rosa-1015 repo

```bash

git remote rm origin

```

### 3. Link your own GitHub repository

```bash

git remote add origin <your repo URL>

```

## 🚀 Getting Started

### Install dependencies

```bash

npm install

```

### Run tests in watch mode

```bash
npm run test:watch
```

### View HTML report of test results

After running the tests, a file named test-results.html is generated.
Open this file using the Live Server extension in VS Code to see the test results visually (passed/failed lines in green/red).

## 📝 Extra Notes

-	To open test-results.html, right-click the file in VSCode and select "Open with Live Server".
-	You can press w while the test watcher is running to see other watch options.

## 🔗 Useful Links

- [Jest Documentation](https://jestjs.io/docs/getting-started) – Learn more about writing and running tests with Jest.
- [Live Server Extension (VSCode)](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) – Open `test-results.html` visually.
- [MDN Web Docs - Array methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) – Reference for ES6 array methods (`map`, `filter`, `reduce`, `sort`).
