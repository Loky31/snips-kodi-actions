# Snips Kodi skill

Skill for Snips voice assistant. Allow to remote the kodi application.

## Setup

Add the application on the snips for your assitant.

## Configuration
Modify <b>config.ini</b> to change with your ip and port. Moreover, you can change your favorite application for the command search movie/tv-show.<br>
The name should be lowercase, no space as the following. 'Exodus Redux' become 'exodusredux'.

## Troubleshooting 
> [Home][err] /usr/bin/env: ‘python2\r’: No such file or directory

Seems that DOS chars are in python script. One solution is to use dos2unix and run `dos2unix * ` in the git directory.