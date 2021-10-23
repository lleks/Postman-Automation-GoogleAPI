# Postman Automation GoogleAPI


1. Download and install Node.js.
2. Run `npm install -g newman` in cli.
3. Run `newman run 'collection name' -e 'environment name'` in cli

`npm install -g newman-reporter-htmlextra` - to install report feature

`newman run "C:\...\...\...collection.json" -e "C:\...\...\...environment.json" --reporters cli,junit,htmlextra --reporter-junit-export "newman_result.xml" --reporter-htmlextra-export "newman_result.html"` - run collection + report creating in xml and html formats.
