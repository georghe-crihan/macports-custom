#Custom port files

To enable use from the macports _port_(1) shell, do the following:

1. Edit (uncomment) the last line of _/opt/local/etc/macports/sources.conf_ to
   read
```
   ...
   file:///Users/${USERNAME}/ports
```
   see _sources.conf_(1).   
2. Issue a _portindex_(1) command.

