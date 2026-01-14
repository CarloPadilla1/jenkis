
docker run -d --name jenkins -p 8080:8080 -p 50000:50000 --user root -v /var/run/docker.sock:/var/run/docker.sock -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts
docker ps

f36d3f58351443c89c98625f4bf1d67b

eanpadilla@gmail.com
eanspiegel

docker stop jenkins