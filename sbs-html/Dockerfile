From ubuntu:latest
LABEL "Author" = "Dineshwar"
RUN apt update
RUN apt install apache2 git -y
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
EXPOSE 80
WORKDIR /var/www/html
