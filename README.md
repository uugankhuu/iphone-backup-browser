# iphone-backup-browser
Automatically exported from code.google.com/p/iphone-backup-browser

Welcome to iphone-backup-browser.
This tool makes it easy to browse iPhone backups, extract files and even convert databases into more readable formats.

Features
iphone-backup-browser allows you to

Browse your iDevice backups
Extract files from backups (including, but not limited to pictures, videos, voice recordings)
Convert
Location data into CSV or KML (Google Earth)
Contacts data into vCard (Outlook etc.)
Notes data into HTML
Call history data into CSV
SMS into CSV
Most important calendar data into iCal (Converter does unfortunately not convert recurring events, they will be listed only once.)
Background
I upgraded my iPhone 3Gs to iOS5. But I forgot to backup my databases manually. I did not want to restore my backup made by iTunes because I wanted a clean iOS restore. To get my contacts and SMS back, I wrote this tool and eventually extended with some converters to convert sqlite databases into more usable file types.

If you want, you can do what you want with this code as long as you pay attention to its license. It is no good code I must admit. It is a more-or-less quick and dirty solution. Everything runs in the user interface thread. But this code works, at least for me.

Portions of this code are based on this project, especially the most important information about iTunes' backup files. However, this project did not include all the features I needed, so I wrote this tool.
