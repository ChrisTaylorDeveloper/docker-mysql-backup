# Docker MySQL Backup

Backup up a MySQL database with the mysqldump utility running in a Docker container.

## Useage
```
./docker-mysql-backup.sh --help
```

## Argbash
To add new arguments, update header of `docker-mysql-backup.sh` then try:
```
mv docker-mysql-backup.sh docker-mysql-backup.sh.old
./argbash docker-mysql-backup.sh.old > docker-mysql-backup.sh
rm docker-mysql-backup.sh.old
chmod +x docker-mysql-backup.sh
```
