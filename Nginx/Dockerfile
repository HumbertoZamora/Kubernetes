# docker run -dti --name web -p 8080:8080 nginx-proxy:v1

FROM nginx:stable

USER root

RUN echo "alias ll='ls -ltrh'" >> /etc/bash.bashrc
RUN echo "namesever 8.8.8.8" > /etc/resolv.conf
RUN apt-get update && apt-get -y install vim sudo netcat iputils-ping curl net-tools

# COPY location.conf /opt/bitnami/openresty/nginx/conf/bitnami/location.conf

# CMD ["/bin/bash"]

USER 1001