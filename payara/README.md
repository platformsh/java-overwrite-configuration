
# Payara with JPA

![Hello World Platform.sh and Payara](https://pbs.twimg.com/media/ES1yxFiWoAQnjIg?format=jpg&name=small)

After creating the first plain hello world with Payara Micro and Platform.sh, it’s time to create the first application connected with a SQL database. Payara has support for Jakarta technologies that includes JPA, [Jakarta Persistence API](https://projects.eclipse.org/projects/ee4j.jpa).

[Jakarta Persistence](https://jakarta.ee/specifications/persistence/) defines a standard for management of persistence and object/relational mapping in Java(R) environments.

On this point, we'll create a REST application this time connect to a relational database; we have support to [MySQL, Maria](https://docs.platform.sh/configuration/services/mysql.html) and [PostgreSQL](https://docs.platform.sh/configuration/services/postgresql.html), but on this application we'll use [PostgreSQL](https://docs.platform.sh/configuration/services/postgresql.html).


## Execute

```shell 
curl --location --request POST 'http://localhost:8080/fishes' \
--header 'Content-Type: application/json' \
--header 'Content-Type: application/javascript' \
--data-raw '{"name": "payara"}'
```

```shell
curl --location --request GET 'http://localhost:8080/fishes'
```
