TypeScript Node Skeleton
========================

TypeScript node.js project skeleton


Developing
----------

Install node 16.  You can use nvm to manage node versions.


### First time install ###

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
