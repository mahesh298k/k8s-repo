FROM tomcat:8.0
LABEL author="kumar"
ADD https://sourceforge.net/projects/openmrs/files/releases/OpenMRS_Platform_2.1.4/openmrs.war /usr/local/tomcat/webapps/openmrs.war
EXPOSE 8080
CMD ["bin/catalina.sh", "run"]

# docker build -t openmrs:2.1.3
# docker tag openmrs:2.1.3 alex7777/openmrs:2.1.3
# docker login
# docker push alex7777/openmrs:2.1.3