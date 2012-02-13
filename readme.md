## CHANGES

* backup all databases by default
* exclude data of drupal cache tables by defa
* added support for default credentials
* added fix for problem with information_schema, based on http://bugs.debian.org/cgi-bin/bugreport.cgi?bug=550037
* added support for table per file backup, avoids locking the whole database

## TODO
* https://gist.github.com/1817036
* registry and registry_file tables (D7)
* mysqldump: Got error: 1556: "You can't use locks with log tables." when doing LOCK TABLES