# TribeDoorWeb
SourceCode for TribeDoor


Hello

You will need the following to set up Tribdoor on your native machine

Apache v2.4.6 or greater
Php v5 or greater
MYSQL/MariaDB
FFMPEG

There should be no external javascript dependencies. 


Site is on a Centos7 box


In most php files $tld references the source of the path for the CS directory, please put the cs directory on your machine and alter $tld as you so choose

If you see any passwords or something i missed to omit from a configuration perspective, please let me know. 

Explanation
/CS/  <- This is the directory where all uploaded files and json indexes are kept

/www  <- This is the front facing doucment root

DBStruct <- this is the db structure of the database, popluate with data as needed

httpd.conf   <- This is the additons to the httpd.conf file in order for the alias directories to work when the html is generated. 

Thanks
Michael


