FROM almalinux:8
RUN yum install nginx -y
CMD ["nginx","-g","daemon off;"]
ENV username="hari"
RUN add user $username
USER $username
# WORKDIR /tmp
# RUN echo "hari KRISHNA" > file.txt
# ENV username="hari"
# ADD https://raw.githubusercontent.com/daws-76s/notes/master/session-01.txt /tmp/
# RUN rm -rf /usr/share/nginx/html/index.html
# COPY index.html /usr/share/nginx/html/
# LABEL NAME="HARI KRISHNA"\
#       COURSE="AWS DEVOPS"
# EXPOSE 80/tcp