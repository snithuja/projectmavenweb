# nagioss
docker pull jasonrivers/nagios:latest
docker images
docker run --name nagios4 -d -p 8888:80 jasonrivers/nagios:latest
docker start -ai nagios4
