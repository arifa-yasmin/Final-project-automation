## Running Tests Individually

**1. To run specific test files individually, use the following commands:**
   ```
   1. npx wdio wdio.conf.js --spec ./test/specs/test-1.js
   2. npx wdio wdio.conf.js --spec ./test/specs/test-2.js
   3. npx wdio wdio.conf.js --spec ./test/specs/test-3.js
   ```

## Running All Tests Sequentially

**1. To run all tests sequentially and generate the report, use:**
   ```
   npx wdio run wdio.conf.js
   ```

## View Allure Report
**1. Generate the Allure Report:**
   ```
   allure generate allure-results --clean -o allure-report
   ```
**2. Open the Allure Report:**
   ```
   allure open allure-report
   ```




