# http server

### Build Image
docker build -t apache-website .

### Create container
docker run -d --name apache-website-01 -p 80:80 apache-website