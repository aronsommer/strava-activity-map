# strava-activity-map

A web app that loads all activities from a user's Strava account and displays them in a Leaflet app.
Based on this repo: https://github.com/nsynes/ActivityMap

How to deploy your Node.js app to Google Google Cloud:
For Google Cloud set environmental variables (.env file) with an app.yaml file in repo
1. Create a Project in Google Cloud
2. Create Application in App Engine (navigate to App Engine via the left sidebar)
3. Open Cloud Shell and clone git repo into home directory of project:
```git clone https://github.com/username/reponame.git```
4. Change into your repo directory: ```cd reponame```
5. Install the dependencies: ```npm install```
6. Make sure your package.json has a working start script!
7. Run ```npm start``` than preview via "Web Preview" symbol (Set correct port)
7. Deploy: ```gcloud app deploy```

How to update project in Google Cloud App Engine:
1. Open project in Google Cloud
2. Open Cloud Shell and cd into your repo directory: ```cd reponame```
3. Pull git updates: ```git pull origin main```
4. Deploy new version to Google Cloud: ```gcloud app deploy```
