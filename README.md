
docker beta for OS X consistently crashes while running this script. docker via toolbox and virtualbox does not crash running this script.

How to reproduce:

1. Start Docker beta for OS X
2. `git clone git@github.com:chrishiestand/docker-mysql-import-bug.git`
3. `cd docker-mysql-import-bug`
4. `./container-start`
5. `./reproduce-beta`

An error log is in `docker-system.log`
