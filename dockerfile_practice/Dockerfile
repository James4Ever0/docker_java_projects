FROM --platform=linux/arm/v7 tomcat
# you just cannot use the image written on that textbook. 
MAINTAINER whatever

# this COPY command will create parent directory if have to.
# notice: this path is wrong.
#COPY index.html /usr/tomcat/webapps/ROOT/

# this is correct
COPY index.html /usr/local/tomcat/webapps/ROOT/
# who the fuck know the exact path of this docker file?
# create that file first please?
EXPOSE 8080/tcp
