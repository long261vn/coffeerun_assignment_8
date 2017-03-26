# coffeerun_assignment_8
CPSC 473 - Assignment 8

Section 2 due April 3. Section 1 due April 5.

In this assignment, you will finish the CoffeeRun app, complete a Programming Challenge, and modify the app to work with a new back-end.

Complete the following:

1. Work through Chapter 13 to connect CoffeeRun to a back-end service.
2. Complete the SIlver Challenge: Validating Against the Remote Server .

Note: Steps (3) through (6) may be completed either before or after working through Chapter 14.

3. From the command line, install the json-server tool with npm install -g json-server then switch to your coffeerun/ directory.
4. Download db.json from GitHub. Place it in your coffeerun/ directory, then start the server with json-server --port=3002 --watch db.json
5. Modify SERVER_URL in scripts/main.js to use http://localhost:3002/coffeeorders
6. Update scripts/remotedatastore.js as necessary to use the local json-server as CoffeeRun’s new back end.

Note that you will need to make changes to the way that orders are created. These changes should not affect the rest of the code.
Hint: POST a new order and see how the newly-created order differs from the order currently stored in db.json .

7. Work through Chapter 14 to switch over to Promises and JQuery Deferred objects when storing data.
8. Push the contents of your coffeerun directory into a new public GitHub repository

Grading
How to know if the assignment has been successfully completed:

1. Is there a .eslintrc.json file?
2. Have you fixed any issues detected by the linter-eslint plugin?
3. Have you run the atom-beautify plugin?
4. Have you fixed any JavaScript issues displayed in the DevTools Console?
5. Is there a new scripts/remotedatastore.js module?
6. Is json-server installed and running?
7. Is SERVER_URL pointing to json-server ?
8. Does the CheckList show the orders stored in the back-end service?
9. Are you able to add rows to the CheckList by submitting the order form?
10. Are you able to make deliveries by clicking rows in the CheckList?
11. Are you able to see orders being added and removed from db.json ?
12. Has the code been updated to use Promise objects with the local DataStore ?
13. Has the code been updated to use Deferred objects with the RemoteDataStore ?
14. Do you have a new repository for this assignment?
15. Have you checked in the changes from this assignment and pushed them to GitHub?
