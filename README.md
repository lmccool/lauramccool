<h1>Deployment Plan</h1>
<h2>Laura McCool August 2014</h2>

<h2>Local</h2>
Create a branch for new feature
In terminal input "git branch newFeatureName" then "git checkout new feature name"

Build and test the feature locally
Merge completed new feature with master branch
In terminal input "git checkout master" then "git merge new feature name""

Server: Staging
Push new feature to staging server
In terminal "git push StagingServer master"
Test feature live on the staging server

Server: Production
Once you are finished testing and everything is working, push to production server
In terminal input "git push LiveServer master"
Test new feature live on the production server