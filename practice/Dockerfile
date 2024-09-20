FROM almalinux:8
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
RUN yum install nginx -y
ENV NAME="HARI"
CMD ["nginx","-g","daemon off;"]
# LABEL NAME="HARI KRISHNA"\
#       COURSE="AWS DEVOPS"
# EXPOSE 80/tcp