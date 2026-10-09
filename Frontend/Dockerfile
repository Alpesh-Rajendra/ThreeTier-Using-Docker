FROM amazonlinux
RUN yum update -y
RUN yum install httpd -y 
COPY index.html /var/www/html/index.html
EXPOSE 80
CMD ["httpd", "-D", "FOREGROUND"]
