# pms-volmarg-issues

1. apcu extension install

2. Database host issue - 

```
    # DATABASE_URL=mysql://root:password@mariadb/pms # database connection setting
    Working - DATABASE_URL=mysql://root:@127.0.0.1:3306/pms # database connection setting
```
3. Commands -
```
bin/console doctrine:schema:update --env=dev --force
bin/console doctrine:migrations:migrate
```
