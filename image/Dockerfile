# Losen-mqtt-collector image
FROM node:latest
MAINTAINER Abhishek <abhishekn.sharma@gmail.com>
RUN apt-get -qq update
RUN apt-get -qqy install git
RUN git clone https://github.com/abhishekns/MQTT-Broker-Health-Check.git
RUN cd MQTT-Broker-Health-Check  && npm install
# Run
CMD ["node", "/MQTT-Broker-Health-Check/publish.js"]
