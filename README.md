# 9.1 Mid-Module Assessment Practice

## Assessment Setup

### Getting started

1.  Fork and clone this repository.
1.  Open up the repository in VSCode.
1.  In your VSCode terminal, run `npm install`

### Tests

To run the tests, you can run the following command from the command line. You will need to be in the root directory of your local directory.

```
npm test
```

This will run the test output once.

### Test watcher

If you'd like, you can have the tests run constantly. This means that each time you save your file, your tests will re-run. To do so, you can run the following:

```
npm run watch
```

Follow the on-screen prompts to exit out of the constant runner.

### Run tests individually

_After choosing a specific file to run,_ you can also specific which test you want to run, specifically. Add `.only` after either `test` or `describe` for the specific test you'd like to run.

```js
test.only("should return an array of everyone's name who is in the line, in order", () => {
```

This will either run the specific `test` or, in the case of adding `.only` to a `describe`, all of the tests for a specific function.

> **NOTE:** Don't forget to remove this after you get the test to pass!

### Run file

If you want to manually test out your file, you can do so by running the following command.

```
node index.js
```

The output will be printed to your terminal.

### Existing files

This repository contains the following file that you will want to take a look at:

- `data/swapi.js`: This is the data that you can expect to be inserted into your function.
- `index.js`: This is where you will write your code. This is the only file you should need to edit.

### Function descriptions

You will find instructions, examples and descriptions in the `index.js`.
Use the JSDoc instructions, Jest tests and commented examples as your guide.

Good Luck!
