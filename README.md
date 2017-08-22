# docker-java8-jenkins-etc


Sets up a container with jenkins installed listening on port 8080.

# Usage

To run the container with the same time zone as the host, do the following:

sudo docker run --restart=always -t -i  -p 8080:8080 -v /etc/localtime:/etc/localtime:ro {build image name}
To start Jenkins from the container's command prompt . . .
java -jar opt/jenkins.war

cf - https://github.com/TexaiCognitiveArchitecture/docker-java8-jenkins-maven-git-nano
