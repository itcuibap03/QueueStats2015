# QueueStats2015
Simple yet informative queue stats viewer.  Works in all major distros.

Instructions:

In FreePBX: Admin>Module Admin> Make sure PHPAGI Config module is installed. If not, install it.

Goto Settings>Asterisk Manager Users> Add Manager with a name like queuestats and a complex password. ReadRead/Write all. Submit changes.

Goto Settings>PHPAGI Config> under Asterisk API settings Choose Manager: queuestats. Submit changes.

Put files in /var/www/html/ into a folder like queuestats

Browse to http://freepbxip/queuestats/ and there it is!

NOTE: Queue members must be dymamic.  In your queue settings make sure to set reset queue stats nightly/weekly.
