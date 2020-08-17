#This is a sample Image
FROM ubuntu
MAINTAINER toxin196@gmail.com

# install packages
RUN apt-get -y update
RUN apt-get install -y screen
RUN apt-get install -y wget

# download factorio
RUN wget --content-disposition "https://www.factorio.com/get-download/latest/headless/linux64" -P /opt

# unzip dedicated_server
RUN ls -la /opt/
RUN tar -xf /opt/*.tar.xz*

CMD [“echo”,”Image created”]
