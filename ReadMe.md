To run dockerized application, 

- Linux containers
run:

```
docker build -t aspnetapp .
docker run -d -p 8080:80 --name hellonetcore aspnetapp
```

- Windows containers (Switch to Windows containers)

```
docker build -t aspnetappwindows . -f DockerFile.Windows
docker run -d -p 8080:80 --name hellonetcore aspnetappwindows
```