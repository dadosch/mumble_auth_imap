# A small python program which allows you to authenticate Murmur against IMAP (Dovecot, etc.)
A fork of https://raw.githubusercontent.com/mumble-voip/mumble-scripts/master/Authenticators/SMF/2.0/smfauth.py
Please note: *The UID which is needed is generated through the login name (your email) and has to be cutten off after the 9th digit, because otherwise we get an error. This might be an security 
issue for you. Only you are responsible for things you are running!*

## Installation
 - Put the .py and .ini file somewhere on your system and run it (preferably *NOT* as root) whenever Murmur is run.
 
## Configuration
 - Make sure you have enabled ice in Murmur config.
 - On Ubuntu, install packages `python3-zeroc-ice zeroc-ice-slice` in a addition to your python environment
 - Make sure you install `IMAPClient` for python3, for example with `pip3 install IMAPClient`
 - Configure .ini file as needed
