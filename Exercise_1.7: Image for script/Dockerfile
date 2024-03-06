FROM ubuntu

WORKDIR /usr/src/app

COPY my_program.sh .

RUN apt-get update && apt-get install -y curl
RUN chmod +x my_program.sh

CMD /usr/src/app/my_program.sh
