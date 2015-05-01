FROM aviata/java7 

MAINTAINER jmarsh.ext "jmarsh.ext@aviatainc.com"

RUN wget https://dl.bintray.com/sbt/debian/sbt-0.13.8.deb
RUN sudo dpkg -i sbt-0.13.8.deb

RUN mkdir /opt/app

WORKDIR /opt/app/mystuff/

EXPOSE 9000
EXPOSE 9999 
RUN ["bash"]
