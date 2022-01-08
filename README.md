# mysql-docker

A docker compose file to run docker for local development purposes.

## How to run ?

Make sure you have docker installed. Then simply run:
```
docker compose up
```

If you want to rebuild the image:
```
docker compose up --build
```

This will run the mysql instance on your localhost port `3306` which can be accessed via any mysql client or by using MySql Workbench.
