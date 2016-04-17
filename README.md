# BackupRaspberry

# Moritz Gelb
# April 2016

Descripton:
Some cronjob scripts running on a Raspberry Pi or any other machine for doing backups of repositories.

Hints:
Specifiy the backup-volume, your repositories in the files
If you use a private repository you might have to add the correct ssh-key. Cronjobs are sheduled by root. 
Please note that you have to configure ssmtp to send mails: https://www.nixtutor.com/linux/send-mail-with-gmail-and-ssmtp/
Finally put the scripts into /etc/cron.daily

