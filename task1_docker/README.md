# Задание 1
В терминале выполняла команды:

```
docker build . --tag=docker_task1
```
```
docker run -d --name=task1 -p 8889:80 docker_task1
```
```
curl localhost:8889
```