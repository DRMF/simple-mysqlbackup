simple-mysqlbackup
==================

bash script to backup your databases

##Parameters##
<code>STORAGEDIR</code> = Folder where the script stores your backup.

<code>IGNOREDB</code> = List of Databases to ignore.

<code>ROTATION</code> = Number of days the backup should rotate. Default is 7.

Crotab
======

For regular updates create a new cronejob <code>crontab -e</code> and insert the following contents
<code>
0 0 * * * /home/vagrant/simple-mysqlbackup/mysqlbackup.sh
</code>

Suggestions
===========
If you have suggestions to improve the script, please let me know!
