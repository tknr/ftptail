ftptail was written by [Will Moffat](http://hamstersoup.wordpress.com/about-will/) 
========

**ftptail** allows you to tail logs via FTP.  Will didn't seem to have a github page so I am putting it up here to get this awesome bit of code out there. 

example:
ftptail -v -f -e cp932 -p ~/.password/ftp_password.txt ftpuser@ftpexample.com/log.txt
