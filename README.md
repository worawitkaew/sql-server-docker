 ###### first aws? (yum is hard to have docker-compose)

 ### Amazon linux
 ---
 (yum is hard to have docker-compose)
 ---
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

    - start docker `systemctl start docker`

### Ubuntu 
---
if you use Ubuntu apt intead of yum
---
- `sudo apt update`
- `sudo apt upgrade`
- `sudo apt-get install git`
- `sudo apt-get install docker`
- `sudo apt-get install docker-compose`

 ### How to have Sql server?
- [tutorial](https://www.dotnetthailand.com/storage/sql-server/docker-compose-for-sql-server)
- Host=localhost
- Port=1433 (default port number, you can ignore)
- Database=msdb
- Username=sa
- Password=12345Abc%