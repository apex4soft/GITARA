FROM ubuntu:20.04
RUN apt-get update
RUN apt-get install -y vim curl 
COPY ./scriptname.sh /app/
WORKDIR /app
RUN chmod +x scriptname.sh
ENTRYPOINT ["bash", "scriptname.sh"]


