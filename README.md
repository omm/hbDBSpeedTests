# hbDBTest
Harbour DB speed test comparation - Registers Count: 821051

### MySql configuration( 1 or 2 ) 

1) /data/mysql/dbstru.zip  - Import structure of Database and then with importDbf.prg transfer all dbf data to mysql
2) /data/mysql/db.zip - Import all database file to mysql

### Dbf configuration

1) unpack /data/dbf/db.zip

### LetoDB configuration

1) /data/letodb.ini <- Set the "Datapath" with your full path to dbf folder. FIRST OF ALL!!!!
2) /data/letodb.exe install <- Install letodb Service
3) /data/letodb.exe start <- Start letodb Service(Check Windows Services if started)
4) /data/letodb.exe stop <- Stop letodb Service

/data/letodb.exe uninstall <- Uninstall letodb Service
