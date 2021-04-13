# 541-Relational-Algebra-Project
------------------------------------------------------------------------------------------------------------------------------------------------------
    Disclaimer
------------------------------------------------------------------------------------------------------------------------------------------------------

Please do not steal the code for this project. We (Noah Bledsoe and Michael Hammond, i.e. the project creators) worked very hard on this code and we cannot     guarantee your institution will not penalize you. We hold no responsibility for the legal, moral, and ethical penalties you may face for having been a filthy pirate.

For ***employers*** who wish to see the code, contact us at nbledsoe@radford.edu (Noah) or mhammond9@radford.edu (Michael) to view the unlisted Gist which contains the code.

Santa is watching.

------------------------------------------------------------------------------------------------------------------------------------------------------
    About
------------------------------------------------------------------------------------------------------------------------------------------------------

  - This is a Database project developed in Java Designed to take Relational Algebra functions as Input
  - Writes each table to Disk before being printed
  - Supported RA Functions:
    - Project
    - Restrict
    - Join
    - Hash Buckets
  - Tables in this project are known as Tilde Tables.
  - Writes a backup of the table to disk before printing - useful if you want to query any other tables.

------------------------------------------------------------------------------------------------------------------------------------------------------
    Compile and Run
------------------------------------------------------------------------------------------------------------------------------------------------------
   - Run Shell Parsers (Assuming Linux and other Linux dependencies in Programs are Installed):
    - Run Hash Table Parser                 : `./progparser.sh`
    - Run Prefix Strip Parser               : `./timecustdump.sh`
    - Run Tilde Table Reorganization Parser : `./steptwo.sh`
   
   - Compile and run Java:
    - Compile                               : `javac *.java`
    - Run                                   : `java Driver.java`  
------------------------------------------------------------------------------------------------------------------------------------------------------
    File Information
------------------------------------------------------------------------------------------------------------------------------------------------------
 - `Driver.java`       - Main executable program which supports functions other than hashing
 - `DriverHash.java`   - Main executable program which supports hashing
 - `Algebra.java`      - Most of the actual code, this is where the Relational Algebra database functions lie

 - `progparser.sh`     - Linux Shell Script which parses a hash table into usable buckets
 - `timecustdump.sh`   - Linux Shell Script which parses the first tilde in every row out of the table
 - `steptwo.sh`        - Linux Shell Script which formats the table into a usable tilde table.
