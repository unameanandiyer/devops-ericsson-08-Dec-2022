# Base Image 
FROM ubuntu:16.04 

# Maintainer
MAINTAINER Amit Vashist <amitvashist7@outlook.com>

# Update the APT Repo 
RUN apt-get update 

# Install Apache Packages 
RUN apt-get install apache2 -y 

# Bring the Apahe Serice UP
CMD [ "/usr/sbin/apache2ctl", "-D", "FOREGROUND" ]
