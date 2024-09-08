# Template wp-site-dockerized

This is a template for initializing a wordpress project.

### Requirements 

- existing MySQL Database
- docker network named **nginx-proxy**
    - `docker network create nginx-proxy`
- (OPTIONAL) Running [easy-multidomain-docker-server](https://github.com/jaretburkett/easy-multidomain-docker-server)
- (OPTIONAL) Owning a domain name and having it registered to your deployment IP

** Some requirements are optional and should be considered for deploying with a domain name using the proposed dockerized reverse proxy nginx service