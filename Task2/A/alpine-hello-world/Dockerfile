FROM alpine-gcc 

COPY main.cpp /usr/hello-world/

WORKDIR /usr/hello-world

RUN g++ -o Main main.cpp

CMD ["./Main"]

