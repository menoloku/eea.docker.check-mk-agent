# eea.docker.check-mk-agent
Docker container running check_mk_agent-1.2.8p26-1 and xinetd.
Easily install check-mk-agent on docker hosts.
Base image - latest centos image.
Configuration for logwatch plugin added.
Listen only on IPv4, TCP, port 6556.
# Usage example
docker run -it -d --name=check_mk-agent -p 6556:6556 eeacms/check-mk-agent
