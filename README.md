archived-artifact-url-viewer
============================

Jenkins plugin to view contents of a file inside a zip or jar file under a subdirectory of artifacts directory of a build
The url to access a file inside a zip or jar archive within the artifact folder of a build is as follows

/archivedArtifacts/artifact/<job_name>/<build_number/<relative location of zip or jarfile within artifact folder>/<location of file within archive>
Ex: 

http://<jenkins_url>/archivedArtifacts/artifact/Build%20-%20Dev/10526/junit-logs.zip/junit.log

