
#to create
docker build . -t blob:v1

#to run in interactive moude
docker run -i -t --env-file .env --privileged blob:v1 /bin/bash
