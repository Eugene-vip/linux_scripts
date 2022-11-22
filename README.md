# useful linux scripts and commands

### Create archive files and directories with current date name
tar cf /home/backup_archive/pg_backup_$( date '+%Y-%m-%d_%H-%M-%S' ).tar -P /home/backup/
