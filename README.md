# cicd-pipeline-train-schedule-jenkins

This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities.

##
## Running the app
##

You need a Java JDK 7 or later to run the build. You can run the build like this:

    ./gradlew build

You can run the app with:

    ./gradlew npm_start

Once it is running, you can access it in a browser at [http://localhost:3000](http://localhost:3000)

===========================

set on a master # of executors 0
changed on a worker node: "only build jobs with label expressions" to "use this node as much as possible"
Worked. Now trying to see if push wil work
