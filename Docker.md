1. create yourgithubid/webserver
1. Populate it with an appropriate Docker file and index.htm (as, for example, in this repo)
1. create a dockerhub account http://hub.docker.com
1. at top right click on create and then "Create automated Build"
1. select github (on the left)
1. select your forked project yourgithubid/webserver
1. click on create

Now every time you push a commit to the github repo, the new container is created on DockerHub.

You can access them from any machine via
```
docker pull yourDockerId/webserver
```
