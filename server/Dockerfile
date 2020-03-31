FROM golang:1.14

WORKDIR /go/src/server

RUN go get -u github.com/gin-gonic/gin \
    && go get -u github.com/jinzhu/gorm \
    && go get -u github.com/go-sql-driver/mysql
CMD bash