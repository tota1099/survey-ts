docker run --name survey -p 27017:27017 -v $(pwd)/db_mongo:/data/db -d mongo:4.2.0
docker start survey
chmod 777 -R db_mongo/