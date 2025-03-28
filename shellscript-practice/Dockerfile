path = /Shellscript_2024/scripts_list
copying file to container

FROM ubuntu:22.04
WORKDIR /home/ubuntu/test
RUN pwd
RUN echo "hi wlecome to docker" >> fileDD01
COPY . .
CMD ["/bin/bash"]
====================================================

FROM ubuntu:22.04
WORKDIR /home/ubuntu/test
RUN pwd
RUN echo "hi wlecome to docker" >> fileDD01
COPY . .
CMD ["/bin/bash", "./Shellscript_2024_/scripts_list/fact.sh", "5" ]
-----------------------------------------------------------------------
override the CMD 
sudo docker run -it my_imagef3 "/bin/bash" "/home/ubuntu/test/Shellscript_2024/scripts_list/fact.sh" "15"

==================================================================================
copying tomcat link

FROM ubuntu:22.04
WORKDIR /home/ubuntu/test
RUN pwd
RUN echo "hi wlecome to docker" >> fileDD01
COPY . .
ADD https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.102/src/apache-tomcat-9.0.102-src.tar.gz .
CMD ["/bin/bash", "./Shellscript_2024/scripts_list/fact.sh", "5" ]
