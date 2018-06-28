# How to Use

* Slack is still third party plugin for sonarqube
* Clone and build app from https://github.com/kogitant/sonar-slack-notifier-plugin
* Put the build file from target folder under $SONAR_HOME/extensions/plugin
* Restart sonarqube and nginx (nginx is usedd in the frontend)
* Best to use it under a docker image with psql db RDS
* Configure slack with incoming webhook
