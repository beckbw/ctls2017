# Best Practices in Data Management and collaboration

### Course Objectives

This course is designed as an introduction to managing data on high performance computing clusters. It is intended to teach users to be self-sufficient and proactive in managing their own data in order to (1) increase their productivity, (2) maximize the usage of the existing storage, (3) decrease accidental or unintentional data loss, and (4) prevent disruption of the file system or compute nodes to the point where it may affect others. This course is intended for people who have beginner to intermediate familiarity with a command line interface, and have active accounts on a TACC HPC cluster.

This course is divided into four modules:

 1. [Overview of HPC Data Management](#mod1)
 2. [Navigating a File System](#mod2)
 3. [Moving and Backing up Data](#mod3)
 4. [Tips and Tricks for Maximizing File System Usage](#mod4)


### Instructional Objectives

This course should be taught in a room equipped with computers (or attendees with laptops) and internet access. Attendees should also have an existing allocation on a TACC resource. Attendees without an allocation can still participate in most components if they have a Mac / Linux laptop, or a Windows laptop with Putty installed and access to a Linux server.


### Specific Learning Objectives


| [Module 1: Overview of HPC Data Management](data_management_01_01.md) <a name="mod1"></a> |
| --- |
| **Topics covered in this module:** |
| • Why do we need best practices in data management? <br/> • Types of file systems used in HPC (NFS, GPFS/Lustre, LTFS, RAID). <br/> • Specific examples of storage infrastructures (TACC Stockyard, Ranch, Corral, `$WORK`, `$SCRATCH`). <br/> • Active vs. inactive data. <br/> • Staging data for compute, analysis, long term storage. |
| **Attendees should be able to...** |
| • List multiple reasons for good data management. <br/> • Describe the similarities and differences of distributed and parallel file systems. <br/> • Determine whether data is backed up or vulnerable. <br/> • Differentiate between active and inactive data. <br/> • Identify the appropriate storage spaces for data at different stages of its life cycle.   |


<br/>

| [Module 2: Navigating a File System](data_management_02_01.md) <a name="mod2"></a> |
|---|
| **Topics covered in this module:** |
| • Introduction to file system limitations (file size, number of files / inodes). <br/> • Determining the size and age of a file. <br/> • Determining the size of a directory, local disk usage (`du, du -h`). <br/> • Total amount of free disk space (`df, df -h`). <br/> • Checking your quota (`quota, lfs quota`).  |
| **Attendees should be able to...** |
| • Recognize file size and number limitations for a given file system. <br/> • Measure and report the size and age of a file and directory. <br/> • Measure and report disk usage. <br/> • Measure and report the total amount of free disk space. <br/> • Find different storage system mounted to a HPC cluster. <br/> • Determine their disk quota for various file systems.   |


<br/>

| [Module 3: Moving and Backing up Data](data_management_03_01.md) <a name="mod3"></a> |
| --- |
| **Topics covered in this module:** |
|• How old is your data and when is it time to archive it? <br/> • Zipping and archiving files and directories (`gzip, gzip -r9, gunzip, tar -czf, tar -xzf`). <br/> • Transferring data from point to point (`rsync, scp, sftp, WinSCP`). <br/> • Staging data on Ranch tape filesystem for archiving.  |
| **Attendees should be able to...** |
|• Judge whether it is appropriate to keep active or archive data. <br/> • Zip and unzip files with gzip / gunzip. <br/> • Compress and extract archives with tar. <br/> • Transfer data efficiently between systems. <br/> • Stage data on a tape file systems for transferring to and from.  |


<br/>

| [Module 4: Tips and Tricks for Maximizing File System Usage](data_management_04_01.md) <a name="mod4"></a> |
| --- |
| **Topics covered in this module:** |
|• Best practices in directory organization; dates and file names. <br/> • Get rid of duplicate copies of data and duplications within data (dedupe). <br/> • Share files with colleagues instead of duplicating them (permissions - `chmod`, `chown`, `chgrp`; access control lists; `ln`). <br/> • Don’t install common software in your home directory.  |
| **Attendees should be able to...** |
|• Differentiate organized vs. unorganized data. <br/> • Describe strategies to keep data well organized; especially in the context of job submission. <br/> • Remove duplicate copies of data where appropriate. <br/> • Set the correct permissions for sharing data where appropriate.  |



<br/>

Next: [Data Management](data_management_01_01.md) | UP: [Data Management Overview](data_management.md) | Top: [Course Overview](../../index.md)

<br/>
&copy; 2017 Texas Advanced Computing Center
