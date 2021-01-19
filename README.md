# guacamole-postgres

Alpine Linux based PostgreSQL container pre-populated with database for Apache Guacamole.


## Local testing


* **Optional**: create `.env` file with passwords

```
POSTGRES_USER=some_new_postgres_username
POSTGRES_PASSWORD=some_new_secure_postgres_password
```

* Start the stack

```
docker-compose up
```

*  Open up a web broser and navigate to [http://localhost:8080/guacamole](http://localhost:8080/guacamole)
* Login as **guacadmin** with password **guacadmin**.

