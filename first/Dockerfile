FROM ubuntu:trusty
MAINTAINER PRASHANTHKUMAR@WFS.COM
RUN apt-get update && apt-get -y install apache2 
EXPOSE 80
CMD ["service", "apache2", "start"]


FROM ubuntu:trusty
MAINTAINER PRASHANTHKUMAR@WFS.COM
RUN apt-get update && apt-get -y install apache2   && service apache2 restart
EXPOSE 80
CMD ["ping", "google.com"]

FROM ubuntu:trusty(u have to tell ur depend upon what)
MAINTAINER - organization name or ur name
run - what has to be run for install.
There can only be one CMD instruction in a Dockerfile. If you list more than one CMD then only the last CMD will take effect.
CMD is to provide executable executing container.
expose - listens on the specified network ports at runtime
cmd - can also be overwritten
