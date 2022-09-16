# File_Packer_Unpacker
- The Project is used to perform process monitoring activity.

- Using the project we can fetch data from all files and merge it into one file, also we can extract all packed file whenever required

# Platform Required
Windows NT platform or Linux

# Architectural requirement
Intel 32 bit Processor

# User Interface
Graphical User Interface

# Technology used
Java Programming

# Features of the Project
This Project is Divided into two Parts Packing and Unpacking

1. PACKING ACTIVITY:  

- Here we accept directory name and file name from user.

- we have to create new regular file as the name specified by user.

- Now open the Directory and traverse each file from that directory.In newly Created file write Metadata as header and actual file data in sequence.

- Each name of file, its size and checksum should be writtened in log file whuich gets created in system directory.

- After packing display packing report.

2. UNPACKING ACTIVITY:

- Here we accept packed file name from user.

- for authentaction of packed file use any logic like magic number.

- Open the packed file in read mode and perform below activity as
    
    - Read header
    
    - From the name specified in header create new file.
    
    - write data into newly created file from packed file.
    
    - Repeat all above steps till we reach the end of the unpacked file.
    
    - After Unpacking display unpacking report.
 
 # Application
 Main Purpose of the project is to merge large amount of files into one file by avoiding memory wastage.
 
 # Special features
 we also provide data security by using the concept of Encryption and Primary Header check.
 
 For next level data security we can add MD5 Checksum check.
