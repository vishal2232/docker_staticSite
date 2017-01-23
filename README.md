# docker_staticSite
Hosting a website locally using docker.<br>https://hub.docker.com/r/vishal2232/static-site/
##Steps
Pull the docker image<br>
**$ _`docker pull vishal2232/static-site1`_**<br>Run docker image.<br><br> 
***
**$ _`docker run vishal2232/static-site`_** <br>
***
Run the container in detached mode<br><br> 
**$ _`docker run -d -P --name static-site static-site`_**</br><br> 
***
**$ _`docker port static-site`_**<br>
`terminal output:<br>80/tcp -> 0.0.0.0:32769<br>
443/tcp -> 0.0.0.0:32768`<br><br>
***
 now open the url<br>`[http://localhost:32769] (http://localhost:32769)` <br>
