1. create yourgithubid/webserver
1. Populate it with an appropriate Docker file and index.htm (as, for example, in this repo)
1. create a dockerhub account http://hub.docker.com
1. at top right click on "Repositories" and then "Create Repository"
1. select github (at the bottom)
1. select your project yourgithubid/webserver
1. click on create

Now every time you push a commit to the github repo, the new container is created on DockerHub.

You can access them from any machine via
```
docker pull yourDockerId/webserver
```
