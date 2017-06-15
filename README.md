# Docker ZSH terminal for windows

A basic docker container with ZSH installed - this will also mount its own directory, IE anything at the same level as the docker folder into /development on the container, so you can run tasks or just use ZSH etc. Designed for people who want ZSH on windows. Pre-requisites are you have Docker installed on windows.

Just run from the /docker folder

`docker-compose up -d`

to build and run the container - this will mount the current directory above /docker to the container_name - then

`docker exec -it development-console /bin/zsh`

to access the console and

`docker-compose down`

when you are finished
