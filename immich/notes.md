DOCKER VERSION
If you get an error unknown shorthand flag: 'd' in -d, you are probably running the wrong Docker version. (This happens, for example, with the docker.io package in Ubuntu 22.04.3 LTS.) You can correct the problem by apt removeing Ubuntu's docker.io package and installing docker and docker-compose via Docker's official repository.

Note that the correct command really is docker compose, not docker-compose. If you try the latter on vanilla Ubuntu 22.04 it will fail in a different way:

The Compose file './docker-compose.yml' is invalid because:
'name' does not match any of the regexes: '^x-'

See the previous paragraph about installing from the official docker repository.



https://immich.app/docs/install/docker-compose/#step-4---upgrading



 so my dumb ass doesnt spend 30 mins trying to figure out why  I cant bring  down the container with docker-compose