# 0x14-mysql

![mysql](https://camo.githubusercontent.com/e62f71d0320859dbbcba4b3c21b3c4173b31dabb9ffcdb0e3b1fdec485034078/68747470733a2f2f7777772e73696d706c696c6561726e2e636f6d2f696365392f667265655f7265736f75726365735f61727469636c655f7468756d622f646966666572656e63655f6265747765656e5f73716c5f616e645f6d7973716c2e6a7067)

The MySQL server provides a database management system with querying and connectivity capabilities, as well as the ability to have excellent data structure and integration with many different platforms.

## Needed Knowledge
 - [What is a primary-replica cluster](https://www.digitalocean.com/community/tutorials/how-to-choose-a-redundancy-plan-to-ensure-high-availability#sql-replication)

 - [MySQL primary replica setup](https://www.digitalocean.com/community/tutorials/how-to-set-up-replication-in-mysql)

 - [Build a robust database backup strategy](https://www.databasejournal.com/ms-sql/developing-a-sql-server-backup-strategy/)

 - ```mysqldump```

## Learning Objectives

 - What is the main role of a database
 - What is a database replica
 - What is the purpose of a database replica
 - Why database backups need to be stored in different physical locations
 - What operation should you regularly perform to make sure that your database backup strategy actually works

## Project Requirements
 - Allowed editors: ```vi```, ```vim```, ```emacs```
 - All your files will be interpreted on ```Ubuntu 16.04 LTS```
 - All your files should end with a new line
 - A README.md file, at the root of the folder of the project, is mandatory
 - All your Bash script files must be executable
 - Your Bash script must pass Shellcheck **(version 0.3.7-5~ubuntu16.04.1 via apt-get)** without any error
 - The first line of all your Bash scripts should be exactly ```#!/usr/bin/env bash```
 - The second line of all your Bash scripts should be a comment explaining what is the script doing

## Installation Guide for mysql 5.7.*

 - First go to site [dev.mysql.com](https://dev.mysql.com/doc/refman/5.7/en/checking-gpg-signature.html) and copy the PGP PUBLIC KEY just immediately under the Notice section to your clipboard.

 - Create a new file in your terminal with a .key extension and paste the PGP PUB KEY copied to clipboard.

 - Then do the following
