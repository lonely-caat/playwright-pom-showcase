This repository houses a straightforward automation testing framework built with TypeScript and Playwright, following the Page Object Model pattern.

To run the tests locally, please proceed as follows:

1. Clone the repository.
2. Ensure you have node.js installed. If not, obtain it from the official website.
3. Execute *npm install* to install the required node modules.
You are now set to run tests using npm run test, which will execute tests in three browsers (Chromium, Firefox, Webkit) simultaneously.

For headed mode testing, modify the *playwright.config.js* to set *headless: false*.
