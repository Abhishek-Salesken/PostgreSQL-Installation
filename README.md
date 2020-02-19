# PostgreSQL-Installation

# Steps to Install Navicate PostgreSQL

1. Download postgresql exe file

2. execute postgresql.exe file
      -----> set Installation directory -----> set password for database superuser(postgres) -----> set port number
3. open 'C'drive go to 
      ----->'Program File' ----->PostgreSQL ----->version(Ex: 9.6) ----->data
      ----> Open pg_hba.conf file set  IPv4 local connections: "host    all             all             0.0.0.0/0            md5"
      ----> Open postgresql.conf set max_connections = 10000
      
# Steps to Create Database :
  1. Create New Connection with postgreSQL
         > Connection Name: can be any name
         > host name/IP address:enter your ip address
         > password:enter password
 Click on 'Test connection' now a new data base connection will be created.
 Right click on created 'connection' go to 'NewDatabase..' now a Data base will be created.

# Steps to Create Table in Database :
      click on database-->Tables--> Add New Table
            -->Enter Fields name,type,Length etc

   
  
   
 
 
      

