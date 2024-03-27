# DEVELOPMENT
- Run server as ./dev.sh
## Files Modified

* dev.dockerfile
* bin/docker-dev-entrypoint
* database.yml
* dev.sh  <!--chmod +x --> #chmod +x

## Commands Run

* docker build -f dev.dockerfile -t project .

* docker run -p 3000:3000 -v $(pwd):/rails project

# PRODUCTION
- Run server as ./prod.sh
## Files Modified

* Dockerfile
* bin/docker-entrypoint
* docker-compose.yml
* .env
* .gitignore
* database.yml
* prod.sh

.env file is to be changed when going on vps

## Commands Run

* docker-compose build && docker-compose up
