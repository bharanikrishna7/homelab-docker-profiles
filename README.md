# homelab-docker-profiles
Repository to manage and maintain docker-compose for home lab services

## Notes
All the listed docker profiles assume that:
* volumes are generated in directory at path `/mnt/data/docker-volumes/`
* If associated volume path is unreachable then docker container will not start.

## Docker Profiles
- [x] netdata
- [x] mysql
  - [x] with sample database
  - [ ] automate sample database generation
- [x] portainer
- [ ] postgresql
- [ ] nexus
- [ ] jenkins