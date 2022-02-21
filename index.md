---
title: "L2jOrg"
---

# Getting Started


## Requirements

* Java 17
* MySql 8


## Build From source

### Get the Source (272 Classic protocol)

#### Cloning the repository

To clone the repository you need to have git installed in your system

```bash
git clone --recurse-submodules https://github.com/L2jOrg/L2jOrg

```

#### Downloading the Source

### Build the project

Inside of project folder run the command, to build and assemble the project. It will create a .zip file inside of folder distribution.

```bash
./gradlew distZip
```

### Execution

Unzip the file created in the Build

#### Database

**Make sure the mysql client is available in the path**

To create the authserver database structure:

* Configure the file authserver/sql/mysql_settings.conf with the database info
* Execute the script authserver/sql/install.sh

To create the gameserver database structure:

* Configure the file gameserver/sql/mysql_settings.conf with the database info
* Execute the script gameserver/sql/install.sh

#### Running the Server

Configure the Authserver and Gameserver database configuration file:

* Configure the file authserver/config/database.properties with database info
* Configure the file gamserver/config/database.properties with database info


Execute the Server 

* Execute the script authserver/authserver.sh
* Execute the script gamserver/gameserver.sh

#### Contributing to source

* Get your access to GitHub
* Create a new branch
* Commit your changes,
* Use Pull request https://github.com/L2jOrg/L2jOrg/pulls

## Using Intellij

[link to tutorial](intellij.md)


## Premium Access

**Get your premium access by helping the team with donation or contribution**

* Get access to branch protocol 286 / 306 / 311 / 338 (ADEN - CLASSIC - ESSENCE)
* Get support on installing server
* Get support on new features
* Help the community

Donate here: 
[Donate]
* 50 Euros one time,  then 10 euros by month (discount will be applied for contributors ! :))
* Contact us on Discord for the premium access
* [Discord](https://discord.gg/RbPgE5V)
