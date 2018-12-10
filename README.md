# How to setup SMB on Mac OSX for PS2 Open Loader
It has been known for long that SMB on Mac OSX doesn't play well with PS2. For a long time a known trick has been to update SMB on Mac OSX using [SMBUp](http://eduo.info/apps/smbup). However the problem with SMBUp is that it doesn't work with OSX  El Capitan and later versions.

This tutorial will show how to setup a SMB server using Docker on your Mac, that will work with PS2 Open Loader.

## Pre-requisite
In order to get started you will need the following:

- Mac with OSX and e.g. High Sierra that will work as SMB server
- (Docker for Mac)[https://docs.docker.com/docker-for-mac/] installed and working
- Somewhere on your filesystem, the required (directory structure)[http://www.ps2-home.com/forum/app.php/page/opl_folder_structure] for PS2OPL. 
