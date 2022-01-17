# TipsNtricks

This file contains various tips and tricks for Salesforce development using VS Code

## Commands

### Open CLI log file
code $home/.sfdx/sfdx.log

### Add logging to command
--loglevel=debug

### Open config file for project usernames
code .sfdx/sfdx-config.json


## Git stuff

### Set username and email to enable commits:
git config --global user.name "My Name"
git config --global user.email my@email.com

### Ignore SSL for project (only behind company VPN)
git config http.sslVerify false
