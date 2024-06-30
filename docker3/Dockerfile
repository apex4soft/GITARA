FROM ubuntu:22.04
RUN apt-get update
RUN apt-get install -y vim curl
COPY ./scriptname.sh /app/
WORKDIR /app
RUN chmod +x scriptname.sh
EXPOSE 80
ENTRYPOINT ["bash","scriptname.sh"]
