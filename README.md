# Load Balancer

run commands :

go run servers.go # to run the backend servers
go run main.go # to run the load balancer
curl http://localhost:8080/ # run this mmultiple times to see different servers hit each time
