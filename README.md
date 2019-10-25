# docker-php5-oci8

tutum-docker-apache-php + Oracle oci8-2.0.8 drivers

#Build
docker build -t tre-to/php5 .
#Run
docker run --rm -d --dns=10.27.1.30 --dns-search=tre-to.jus.br -p 8080:80 --name portal -v ~/www:/app tre-to/php5