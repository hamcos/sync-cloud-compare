# Comparison between Owncloud and Seafile

Please note that the following feature list is based on ours tests and some compared features are completely subjective.

Feature                                              | [Owncloud](http://owncloud.org/)                                                                                | [Seafile](http://seafile.com/)
-------------                                        | -------------                                                                                                   | -------------
Tested version                                       | ownCloud 6.0.3 (stable) on Debian stable (wheezy)                                                               | Seafile 3.0.4 on Debian stable (wheezy)
Revision control                                     | Kind of (not so efficient, no diffs)                                                                            | Yes (based on git and works even for bigger binary files)
Possibility to drop old revisions                    | Yes                                                                                                             | Yes
Backend                                              | PHP, Webserver, SQL Database                                                                                    | C, Python, SQL Database, build-in webserver, optional: Webserver like Apache
Small scale syncing test                             | No complains                                                                                                    | No complains
syncing experience by others                         | Many complains                                                                                                  | Few complains
Performance of the web interface (same resources)    | Slow                                                                                                            | Fast
Sharing folders and files across users               | Yes                                                                                                             | Yes
User groups                                          | Yes                                                                                                             | Yes
LDAP or AD authentication                            | Yes                                                                                                             | Yes
Syncing individual folders                           | [Might](https://github.com/owncloud/mirall/issues/1021), [work](https://github.com/owncloud/mirall/issues/1390) | Yes
Encryption                                           | Symmetric encryption: Only Server side with login password                                                      | Symmetric encryption: Client side and/or Server side, enable/disable and password per library
Web interface                                        | Yes                                                                                                             | Yes
Clients for Windows, Linux, Android and iOS          | Yes                                                                                                             | Yes
Sending messages                                     | No                                                                                                              | Yes
License                                              | [AGPLv3](https://de.wikipedia.org/wiki/GNU_Affero_General_Public_License)                                       | [GPLv3](https://de.wikipedia.org/wiki/GNU_General_Public_License)
Calender                                             | Yes                                                                                                             | No
Task management                                      | Yes                                                                                                             | No
Contacts and contact syncing                         | Yes                                                                                                             | No
Picture galleries                                    | Yes                                                                                                             | No
RSS Reader                                           | Yes                                                                                                             | No
PDF/ODT viewer                                       | Yes                                                                                                             | Yes
Edit text files in Browser                           | Yes                                                                                                             | Yes
Syntax Highlighting                                  | Yes                                                                                                             | Yes
Show the difference between reversions of text files | No                                                                                                              | Yes. Based on git.
Download files from URL to library                   | Yes                                                                                                             | No
Full text search                                     | Yes                                                                                                             | In the Pro Version
Web interface easy customizable                      | [Yes](http://owncloud.org/theming/)                                                                             | [Yes](https://github.com/haiwen/seafile/wiki/Seahub-customization)
