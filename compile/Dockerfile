FROM golang

RUN go get -v github.com/fiorix/freegeoip/cmd/freegeoip \
    && CGO_ENABLED=0 GOOS=linux go build -v -a -installsuffix nocgo -ldflags="-s -w" -o /freegeoip github.com/fiorix/freegeoip/cmd/freegeoip
