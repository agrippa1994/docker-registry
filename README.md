# Docker Registry

## Setup
Set up reverse proxy first for HTTPS support

## Create User and Password
Before starting the compose script, execute the following script below to
generate the htaccess file
```bash
docker run --rm --entrypoint htpasswd registry:2 -Bbn myuser mypassword > ./auth/htpasswd
````

