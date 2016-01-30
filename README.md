# master

## Team

  - __Product Owner__: teamMember
  - __Scrum Master__: teamMember
  - __Development Team Members__: teamMember, teamMember

## Microservices

  - __Front-End Server__
  - __Back-End Server__
  - __In-Memory Storage__
  - __Database__

### Install Procedure

From within the root directory:
  For each microservice

```sh
git clone <microservice repo name>
```

### Run outside of docker:

From within the Back-End-Server directory:

```sh
npm install -g nodemon
npm install
npm start
```

### Run inside of docker:

In Terminal from within root directory:
```sh
docker-machine start <machine-name>
docker-machine env <machine-name>
docker pull ubuntu
docker pull node
docker pull redis
docker-compose up
```
