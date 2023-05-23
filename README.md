# CI
Lab of Continuous Integration with Docker and Jenkins

- Containerized Jenkins server is based on customized image with blueocean plugin installed

- A CI pipeline is reponsible to build image "hit_counter"

- The image is python based webapp with flask

- Docker-compose is called to build frontend (python) + backend (redis)

- /etc/group file inside Jenkins container has to be modified in order to avoid docker sock permission denial
