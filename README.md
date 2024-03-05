# Go helm

## Command line

```bash 

go mod tidy

```


```bash

docker build -t go-helm:latest .

docker run -d -p 9090:9090 --name web-go-helm go-helm:latest
```