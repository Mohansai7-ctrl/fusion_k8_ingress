FROM tomcat:9.0.98-jdk8-corretto-al2
WORKDIR /usr/local/tomcat/webapps/ROOT
RUN rm -rf /usr/local/tomcat/webapps/ROOT/*
RUN echo "Hi, This is from tomcat-fusion" > /usr/local/tomcat/webapps/ROOT/index.html
CMD ["catalina.sh", "run"]