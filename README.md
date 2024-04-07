# psql client run by docker compose

Docker compose for psql client

1. docker-compose run psql bash
2. the above command will start a container for this one-off psql service in a bash shell
3. psql -h postgres -U postgres, run this command in the bash to connect to server, the password is set from server docker-compose
