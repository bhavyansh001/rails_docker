# Files Modified

* dev.dockerfile
* bin/docker-dev-entrypoint
* database.yml
* dev.sh `chmod +x`

# Commands Run

* docker build -f dev.dockerfile -t project .

* docker run -p 3000:3000 -v $(pwd):/rails project