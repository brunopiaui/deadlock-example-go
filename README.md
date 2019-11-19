# deadlock-example-go
Deadlock example in Go

## Running with Docker

### 1 - Install the Docker: https://docs.docker.com/install

### 2 - Clone the project

```
git clone https://github.com/brunopiaui/deadlock-example-go.git
```

### 3 - Go to project folder

### 4 - Build the Docker Image

```
docker build -t deadlock-example-go .
```

### 5 - Run the Docker Image

```
docker run -it --rm --name deadlock-example-go deadlock-example-go
```

---

## Running without Docker

### 1 - Install the Go: https://golang.org/doc/install

### 2 - Get the project

```
go get github.com/brunopiaui/deadlock-example-go
```

### 3 - Go to project folder

### 4 - Run the project

```
go run main.go
```