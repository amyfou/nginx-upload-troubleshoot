# nginx-upload-troubleshoot

colrc: our configuration file (in 'sites-enabled' directory).  Relevant block starts line 46?;
nginx-conf: overall configuration file (pulls in 'sites-enabled directory/colrc');
error.log: our upload attempts to trigger anything here, errors show in access log;
access.log: shows 405 errors on attempts at upload.
