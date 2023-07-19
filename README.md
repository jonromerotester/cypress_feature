- ## 💻 Pre-requisites

1. Node JS
2. Optional: Java 8 for Allure Reporter
3. Optional: Json-formatter for Native Reporter option

## 🚀 Install 

1. Execute: npm init
2. Install Cypress: npm install cypress -save--dev
3. Create Project Name and install dependencies for cucumber
    npm install -D cypress @bahmutov/cypress-esbuild-preprocessor@2.1.5
    npm install @badeball/cypress-cucumber-preprocessor
    npm install @shelex/cypress-allure-plugin

4. Generar proyecto
    npm run test
    node ./cucumber-html-report.js