# addPath
This is a script you can place on path (like /usr/local/bin) and it will allow you to add things to path persistently.

## How to:
For best results, download the file like so:
```
wget https://raw.githubusercontent.com/theregoesmyeye/addPath/refs/heads/main/addpath && chmod +x addpath
```
You now  have my addpath script in the current folder you're viewing. For best results, move it to your path like so:
```
sudo mv addpath /usr/local/bin
```

##Usage:
After following the above intstructions, you should be able to type 'addpath' and a screen that looks like this will come up:
```
                        addPath - Lilith Ivey
                Usage: /usr/local/bin/addpath /path/to/directory
                      Current PATH directories:
                              ====================
                                 /usr/local/bin
                                    /usr/bin
                                /usr/local/sbin
                        /opt/android-sdk/platform-tools
                               /usr/bin/site_perl
                              /usr/bin/vendor_perl
                               /usr/bin/core_perl
                              ====================
[lilith@Rainb0w ~]$
```

To  add a folder to your path, use the following syntax:
```
addpath /path/to/your/folder
```
For example:
```
[lilith@Rainb0w ~]$ addpath Downloads/
Added 'Downloads/' to PATH.
Update saved to /home/lilith/.bashrc. Restart shell or 'source /home/lilith/.bashrc'.
[lilith@Rainb0w ~]$ 
```
From there, type the source command it's giving you **or** restart your shell and your $PATH will be up-to-date!
