From golang:1.18


RUN git clone https://github.com/BizShuk/ginsample.git

# build
WORKDIR ginsample
RUN go build -o /user/app


# run server
WORKDIR /user
CMD ["./app"]
EXPOSE 8080
