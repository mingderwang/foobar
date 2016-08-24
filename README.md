# foobar
rails run with mysql and deploy by docker-compose

➜  foobar docker-compose up
Recreating foobar_db_1
Recreating foobar_web_1
Attaching to foobar_db_1, foobar_web_1
db_1   | Initializing database
db_1   | Database initialized
db_1   | MySQL init process in progress...
db_1   | Warning: Unable to load '/usr/share/zoneinfo/Factory' as time zone. Skipping it.
db_1   | Warning: Unable to load '/usr/share/zoneinfo/iso3166.tab' as time zone. Skipping it.
db_1   | Warning: Unable to load '/usr/share/zoneinfo/leap-seconds.list' as time zone. Skipping it.
db_1   | Warning: Unable to load '/usr/share/zoneinfo/posix/Factory' as time zone. Skipping it.
web_1  | [2016-08-24 15:26:05] INFO  WEBrick 1.3.1
web_1  | [2016-08-24 15:26:05] INFO  ruby 2.2.0 (2014-12-25) [x86_64-linux]
web_1  | [2016-08-24 15:26:05] INFO  WEBrick::HTTPServer#start: pid=1 port=3000
db_1   | Warning: Unable to load '/usr/share/zoneinfo/right/Factory' as time zone. Skipping it.
db_1   | Warning: Unable to load '/usr/share/zoneinfo/zone.tab' as time zone. Skipping it.
db_1   |
db_1   |
db_1   | MySQL init process done. Ready for start up.
db_1   |
^CGracefully stopping... (press Ctrl+C again to force)
Stopping foobar_web_1 ... done
Stopping foobar_db_1 ... done
