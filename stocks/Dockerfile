FROM maven
COPY . /opt/stocks/
WORKDIR /opt/stocks/
RUN mvn clean install
CMD ["mvn", "jetty:run"]
