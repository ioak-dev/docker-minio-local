## Bring up the server locally
docker-compose up -d

## Configure the bucket for use with ioak projects
http://localhost:8086/login
credentials = systemadmin/systemadmin
Create following buckets
- ioaksite
- oneauth
Set "Access Policy" as "public" for all the buckets under Manage bucket page
