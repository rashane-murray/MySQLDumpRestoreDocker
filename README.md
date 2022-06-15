# Load a MySQL Dump File into a new MYSQL container

### Instructions

- Create a data directory and place your dump file. The file should have the extension .sql

- Check the docker-compose.yaml file to ensure that mysql version is correct

- Check the docker-compose.yaml file to ensure that the `MYSQL_USER` and `MYSQL_PASSWORD` are correct

- Run the command `docker compose up` and this will automatically import your sql dump

- You should be able to now login and see all your databases and associated tables

### Additional Consideration

A new directory called MYSQL will be created which will house your actual MYSQL databases. This is a volume that is mapped to the `/var/lib/mysql` directory within the container.