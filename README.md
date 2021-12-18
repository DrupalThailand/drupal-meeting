# drupal-meeting

```
$ lando start
```

```
$ lando drush si --db-url=mysql://drupal9:drupal9@database/drupal9 -y
```

```
$ lando drush rsync @drupalthai.live:%files/ @drupalthai.local:%files/
```

```
$ lando drush sql-sync @drupalthai.live @drupalthai.local
```
