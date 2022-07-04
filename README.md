# Prefect - Docker Compose

A simple guide to understand and make Prefect work with your own docker-compose configuration.

This allows you to package your Prefect instance for Kubernetes or offline use.

![Operating principle of Prefect](./prefect_schema_principle.png)

- [Prefect - Docker Compose](#prefect---docker-compose)
  - [Run the server](#run-the-server)


## Run the server
you can run :

```bash
docker-compose -f server/docker-compose.yml up -d
```
You can login https://localhost with username=testuser, password=testpw for authentication before access into UI of Apollo
You can create user with password by CLI: 
```bash
htpasswd ./auth/nginx.htpasswd another_user
```

