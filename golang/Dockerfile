FROM golang
LABEL app = 'my first app'

WORKDIR gilbert-golang
COPY go.mod .
RUN go mod download
COPY . .
RUN go build -o myfirstapp .
CMD ["./myfirstapp"]