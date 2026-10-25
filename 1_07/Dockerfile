FROM ubuntu:24.04

RUN  apt-get update && apt-get install -y curl

WORKDIR /usr/src/app

COPY script.sh .

RUN chmod +x script.sh

RUN touch additional.txt 

CMD ["./script.sh"]
