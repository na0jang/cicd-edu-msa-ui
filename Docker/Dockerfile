FROM tomcat:9-jre8-alpine
WORKDIR /usr/local/tomcat
COPY ./Docker/server.xml ./conf
RUN rm -rf ./webapps/*
COPY ./edu-msa-ui/target/edu-msa-ui-1.0.0.war ./webapps/edu-msa-ui-1.0.0.war

EXPOSE 28080
