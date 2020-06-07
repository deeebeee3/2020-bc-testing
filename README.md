# 2020-bc-testing
Testing


fix 3 issues:

1) variables scoped to test functions and not globally - so can reuse variable names
2) can now see description for each test we're about to run
3) a failing test won't no longer stop execution - test callback function wrapped in try catch


npm install mocha -g
mocha --version

to use: 
mocha 'name of file' 
mocha index.test.js

