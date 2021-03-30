# Jest - Unit test

## Run

npm install

npm test

## Code coverage in Jest
```bash
npm test -- --coverage
```
or
configuring Jest in `package.json` HTML report for code coverage(you can find the report in `coverage` folder)
```bash
"scripts": {
    "test": "jest"
},
"jest": {
    "collectCoverage": true,
    "coverageReporters": ["html"]
},
```