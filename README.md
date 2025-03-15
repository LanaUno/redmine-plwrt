# redmine-plwrt

Prepare and test

1. Install Node version 20.15.0
2. NPM version 10.7.0
3. Clone repository https://github.com/LanaUno/redmine-plwrt.git
4. Go to the folder redmine-plwrt
5. Install playwright VS Code Extention

   'npm init playwright@latest'

   Run the install command and select the following to get started:

   - Choose JavaScript
   - Name of Tests folder - tests
   - Add a GitHub Actions workflow to easily run tests on CI
   - Install Playwright browsers (default is true)
   - ..playwright.config.js already exists. Override it? (y/N) · select false
   - ..yml already exists. Override it? (y/N) · select false

6. To install all dependencies use npm install
7. Run 'npx playwright test' in the command line to run tests
8. To open last HTML report run: 'npx playwright show-report'

9. To find last HTML report follow the link

https://lanauno.github.io/redmine-plwrt/