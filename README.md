# API Automation Tests

## Prerequisites
- Node.js installed
- Newman installed: `npm install -g newman`
- Newman HTML reporter installed: `npm install -g newman-reporter-html`

## Running Tests
1. Open terminal in repo folder.
2. Run the collection:

newman run "collections/Emilo_API_Tests.postman_collection.json" -e "Environment/AutomationEnv.postman_environment.json" -r cli,html --reporter-html-export "reports/report.html"
