# imapmaillister
Lists mails from imap account - usable with for instance conky or the likes
uses python 3 and should work on most linux machines. Config can be either
provided as arguments or by means of config file.

Usage: imapchecker.py [options]

Simple imapchecker

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -s SERVER, --server=SERVER
                        imapserver
  -P PORT, --port=PORT  server port
  -u USER, --user=USER  username
  -D, --debug           debug
  -p PASSWORD, --password=PASSWORD
                        password
  -d DIRECTORY, --directory=DIRECTORY
                        Imap directory to show
  -c CONFIG, --config=CONFIG
                        Config file to use


### Config file format - default location **~/.imapmaillister**
```
[main]
server = outlook.office365.com
user = user.name@companyexample.com
password = Changeme
directory = Inbox
port = 993
```
