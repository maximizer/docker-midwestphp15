FROM ubuntu:trusty
RUN apt-get update && \
    apt-get -y install php5-cli 
ADD . /app
WORKDIR /app
EXPOSE 8080
CMD ["php", "-S", "0.0.0.0:8080"]
