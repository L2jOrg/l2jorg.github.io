---
title: "L2jOrg"
---

## Getting Started


#### Requirements

* Java 17
* MySql 8


## Build From source

#### Get the Source

###### Cloning the repository

To clone the repository you need to have git installed in your system

```bash
git clone --recurse-submodules https://github.com/L2jOrg/L2jOrg

```

###### Downloading the Source

#### Build the project

Inside of project folder run the command, to build and assemble the project. It will create a .zip file inside of folder distribution.

```bash
./gradlew distZip
```

#### Execution

Unzip the file created in the Build

###### Database

**Make sure the mysql client is available in the path**

To create the authserver database structure:

* Configure the file authserver/sql/mysql_settings.conf with the database info
* Execute the script authserver/sql/install.sh

To create the gameserver database structure:

* Configure the file gameserver/sql/mysql_settings.conf with the database info
* Execute the script gameserver/sql/install.sh

###### Running the Server

Configure the Authserver and Gameserver database configuration file:

* Configure the file authserver/config/database.properties with database info
* Configure the file gamserver/config/database.properties with database info


Execute the Server 

* Execute the script authserver/authserver.sh
* Execute the script gamserver/gameserver.sh

