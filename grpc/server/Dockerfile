FROM library/golang:1.6.0
RUN ["go", "get", "-u", "google.golang.org/grpc/examples/helloworld/greeter_server"]
EXPOSE 50051
CMD ["greeter_server"]

