 ### How to have Sql server?
- bring this to docker-compose.yml
``` text
    sql-server-db:
    container_name: sql-server-db
    image: mcr.microsoft.com/mssql/server:2022-latest
    ports:
      - "1433:1433"
    environment:
      SA_PASSWORD: "strong_password"
      ACCEPT_EULA: "Y"
```