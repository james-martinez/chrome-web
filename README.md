# Browse Google Chrome from Web Browser inside a Docker Container 

If you have a requirement to run Google Chrome browser inside a container we can easily achieve this by using TekFik provided CentOS 7 container. 

TekFik Centos 7 Container image runs google-chrome in command line and exposes TCP port 3000 to access google chrome from the web browser inside the container. 

Refer to the solution given in the following article to run Google Chrome on Docker Container.
  https://www.tekfik.com/kb/devops/google-chrome-on-docker-container
  
  
Refer to steps given in install.txt file if you want to build your own container. 

`docker run --name chrome-web --privileged -p 3000:3000 -d ghcr.io/james-martinez/chrome-web/chrome-web:latest`

`http://localhost:3000`
