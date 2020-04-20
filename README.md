# Sample Wordpress & MySQL docker-compose setup

- Clone the project
- Go into the project and copy the .env file
- Fill out the .env file
- Run docker-compose
- Webiste can be now viewed under `http://localhost`, and a GUI for database can be
  viewed under `http://localhost:8080`.

> Remember to fill each pair of `*_HOST`, `*_USER`, `*_PASSWORD` and (`MYSQL_DATABASE` and `WORDPRESS_DB_NAME`)
with the same value.
> `MYSQL_ROOT_PASSWORD` must be filled in.

```bash
git clone https://github.com/viet-aus-it/wordpress-docker-compose-sample.git
cd wordpress-docker-compose-sample
cp .env.sample .env
# Fill out the env file here

docker-compose pull
docker-compose up
```
