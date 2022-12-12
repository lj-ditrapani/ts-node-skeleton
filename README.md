TypeScript Node Skeleton
========================

TypeScript node.js project skeleton


Developing
----------

### Setup ###

Install node with [nvm](https://github.com/nvm-sh/nvm).

    nvm install     # one-time install
    nvm use         # each time you enter the project directory

Install npm packages.

    npm install


### Run it ###

    npm start


### Format, lint, build, test ###

    npm run all


### Test coverage ###

    # Run the tests with `npm run all` or
    npm test
    # This will generate the test coverage report
    # Then open the test coverage report
    firefox coverage/lcov-report/index.html


### Generate documentation ###

    npm run doc
    firefox docs/index.html &


### Update dependencies ###

    npm run ncu


### Publish ###

    npm login
    npm version patch/minor/major
    npm publish


Author:  Lyall Jonathan Di Trapani
