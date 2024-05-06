# mysql-workspace

## How to use devcontainer


Start the container

```
docker run --name mysql-demo -e MYSQL_ROOT_PASSWORD=root -d  -v $(pwd):/test mysql:5.7
```

Enter the container

```
docker exec -it mysql-demo sh
```