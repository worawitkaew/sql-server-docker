 ### first aws?
 - install git
    `sudo yum install git`
 - install docker
    `sudo yum install docker`
<!-- - install pip -->
    <!-- `sudo yum install pip` -->
<!-- - install docker-compose
    `sudo pip install docker-compose` -->
- install docker-compose
    - go to folder /test
    - `sudo curl -L "https://github.com/docker/compose/releases/download/1.23.2/docker-compose-$(uname -s)-$(uname -m)" -o /docker-compose`
    - `sudo chmod +x /docker-compose`

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