FROM golang:1.22rc2-bookworm
ADD . /go/src/github.com/PagerDuty/go-pagerduty
WORKDIR /go/src/github.com/PagerDuty/go-pagerduty
RUN go get ./... && go test -v -race -cover ./...
