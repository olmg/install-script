install-script
==============

Loggly Sender Installation Script. Sends Linux, Tomcat, Apache, Text file and S3 bucket logs to Loggly.

***Note:*** These scripts support only Loggly **Gen2** account.


You can view the **READMEs** of the various installation scripts at the following paths


1. <a href="https://github.com/psquickitjayant/install-script/blob/master/Linux%20Script/README.md">Linux Configuration Script</a>
2. <a href="https://github.com/psquickitjayant/install-script/blob/master/Modular%20Scripts/Apache2/README.md">Apache Installation Script</a>
3. <a href="https://github.com/psquickitjayant/install-script/blob/master/Modular%20Scripts/File%20Monitoring/README.md">File Monitoring Configuration Script</a>
4. <a href="https://github.com/psquickitjayant/install-script/blob/master/Modular%20Scripts/Tomcat/README.md">Tomcat Configuration Script</a>
5. <a href="https://github.com/psquickitjayant/install-script/blob/master/Modular%20Scripts/S3Logs%20Monitoring/README.md">S3 Bucket Configuration Script</a>
6. <a href="https://github.com/psquickitjayant/install-script/blob/master/Modular%20Scripts/Nginx/README.md">Nginx Script</a>
7. <a href="https://github.com/psquickitjayant/install-script/blob/master/Mac%20Script/README.md">Mac Script</a>


# Modifications by Odyssey
Just needed to change `Linux Script/configure-linux.sh` so that we don't force checking if logs work. It doesn't work for non-interactive shell sessions.
