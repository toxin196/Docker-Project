#This is a sample Image
FROM ubuntu
MAINTAINER toxin196@gmail.com

RUN apt-get -y update
RUN apt-get install -y screen
RUN apt-get install -y unzip
RUN apt-get install -y wget
RUN wget https://www.terraria.org/system/dedicated_servers/archives/000/000/039/original/terraria-server-1405.zip?1591301368
RUN mv terraria-server-1405.zip\?1591301368 terraria-server-1405.zip
RUN mv terraria-server-1405.zip /opt/
RUN unzip /opt/terraria-server-1405.zip -d /opt/
RUN ls -la /opt
RUN chmod +x /opt/1405/Linux/Terraria*

CMD [“echo”,”Image created”]
