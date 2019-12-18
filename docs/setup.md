# New-Website-Process
This is expected to just be a cookbook towards setting up a new website; easy reproducible steps to generate the template structure for a backend Java/PostgreSQL API for communication with a Typescript/React Frontend.

Current intention is to host the front end in Firebase, and the backend in Google Cloud Platform (TBC)

## Frontend
* Roughly following: https://medium.com/@muccy/install-react-with-typescript-in-a-firebase-hosting-project-8db66c59b202
* Generate the app:
`npx create-react-app <APP-NAME> --template typescript`
* install firebase tools
`npm install -D firebase-tools`
* login to firebase/init the functions
* (You'll probably need to make and connect a firebase project to a GCP project for this)
* `npx firebase init hosting`
* `npx firebase deploy`



## Backend
* Create a new 'Project' in GCP:
https://console.cloud.google.com/cloud-resource-manager?_ga=2.36293536.-1881633992.1576528655&pli=1
* 