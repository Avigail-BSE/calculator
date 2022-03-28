[![Board Status](https://dev.azure.com/NBSE/bd57e574-0a9e-4698-9e0a-895a0c53a72c/e582308a-a183-441d-a165-0a2c45a2261a/_apis/work/boardbadge/a07c1217-5927-4796-948c-1cb0c1fe0bf3)](https://dev.azure.com/NBSE/bd57e574-0a9e-4698-9e0a-895a0c53a72c/_boards/board/t/e582308a-a183-441d-a165-0a2c45a2261a/Microsoft.RequirementCategory)
Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

