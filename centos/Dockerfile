FROM centos:latest
MAINTAINER Some Friendly Guy
ADD ./time.sh ./
RUN yum install nmap-ncat -y 
RUN chown 1001:1001 time.sh && chmod o+w time.sh
USER 1001
EXPOSE 8080
CMD ["./time.sh"]
