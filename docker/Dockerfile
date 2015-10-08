FROM jetty
ADD /stocks/target/spring-rabbit-stocks-1.5.0.RELEASE.war /var/lib/jetty/webapps/
RUN java -jar "$JETTY_HOME/start.jar" --add-to-startd=jmx,stats
