Feature                                | Owncloud                                                   | Seafile
-------------                          | -------------                                              | -------------
Revision control                       | Kind of (not so officiant, no diffs)                       | Yes (based on git)
Backend                                | PHP, Webserver, SQL Database                               | C, Python, SQL Database, build in webserver, optional: Webserver like Apache
Small scale syncing test               | No complains                                               | No complains
Sharing folders and files across users | Yes                                                        | Yes
User Groups                            | Yes                                                        | Yes
LDAP or AD authentication              | Yes                                                        | Yes
Syncing individual folders             | [No](https://github.com/owncloud/mirall/issues/1021)       | Yes
Encryption                             | Symmetric encryption: Only Server side with login password | Symmetric encryption: Client side and/or Server side, enable/disable and password per library



