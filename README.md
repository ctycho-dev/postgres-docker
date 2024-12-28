# Docker helper

* start container
docker-compose up -d

* stop container
docker-compose down

* interact with container
docker exec -it db_postgres_db_1 psql -U root

* connect ot db
psql -h 84.201.168.94 -p 5432 -U <user> <db>