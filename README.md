manage credentials [with env](https://stackoverflow.com/a/54023103/564606). If I was using swarm I would use [Docker Secrets]() instead.

use network_mode: "service:pia" for a container to use it,
  move the port mapping from the service into PIA
  
 I decided to place all folders under ~/.media (config, tvseries, downloads)
 
 can view sonarr at <ip>:8989
  
add jackett
  
 write about storing config under git
 
https://www.domysee.com/blogposts/reverse-proxy-nginx-docker-compose
https://www.thepolyglotdeveloper.com/2017/03/nginx-reverse-proxy-containerized-docker-applications/
https://github.com/Sonarr/Sonarr/wiki/Reverse-Proxy#http-non-ssl
 
https://docs.docker.com/network/bridge/
