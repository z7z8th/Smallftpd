 ------------------------------------
 ------------------------------------
   smallftpd   1.0.4
   by Arnaud Mary 
   http://smallftpd.sourceforge.net
 ------------------------------------
 ------------------------------------ 


 1. Description :

    - The first goal of this application was to allow me to specify a hostname to be resolved by the FTP server when going to passive mode.
    - Today, Smallftpd is an open-source project, a simple and small FTP server.
    - Smallftpd needs your remarks, your suggestions, and tour c++ skills !

 2. Installation : 
    
    - run the smallftpd.exe
    - check configuration, create user accounts,
    - press "play". ;-)


 3. Features :

    - Multi-threaded FTP server
    - Active / Passive mode
    - Multi-users
    - Manage List, Read & Write rights for every user
    - Advanced filesystem.


 4. List of supported commands :

    - ABOR, CDUP, CWD, DELE, LIST, MKD, PASS, PASV, PORT, PWD, QUIT, REST, 
    RETR, RMD, RNFR, RNTO, SIZE, STORE, SYST, TYPE, USER.


 5. History :  

    - 1.0.3 Fix (May 21st 2003) :
          * Fixed a stupid bug concerning transfer performances.
          * disabled debug logging
  
    - 1.0.3 :
          * Fixed major security bug (http://securitytracker.com/alerts/2003/Apr/1006685.html)
          * Fixed bug when trying to retrieve a file that does not exist
          * window position is saved
          * display a live estimation of transfer rate in GUI
          * fixed minor bugs
    - 1.0.2 :
          * fixed several [major] bugs
          * some UI improvements
          * ABOR command is now correctly managed.

    - 0.93 alpha :
          * Better UI, window minimizes in systray.
          * Better log system. All transfers are logged in transfers.log           

    - 0.9 alpha ( June 2002 ) :
          * First operational version
          * Added Rename files/folders feature
          * Manage user virtual filesystem
          * Added an inactivity timeout

    - 0.5 ( May 2002 ) :
          * Added Rename files/folders feature  (RNFR & RNTO)
          * Added Delete files feature (DELE)
          * Added Create/delete folder (MKD & RMD)

    - 0.3 ( May 2002 ) : 
          * Configuration is now automatically loaded and saved in a .ini file.
          * Added button icons for ftp running & stopped.
          * Added a List box showing users connected.

    - 0.2 ( April 2002 ) : 
          * Passive mode added. 
          * Also fixed some bugs.
     
    - 0.1 ( January 2002 ) : 
          * very first version.
          * Active mode is supported.


 6. Next features :
 
    - Manage Max number of threads per user / total threads.
    - Reduce Memory taken by process 
    - prevent users from hammering.
    - restrict access by IP
    - check for memory problems. Check Memory overflow possible problems.
    - use CopyMemory, MoveMemory, etc... in order to reduce the size of the .exe file.
    - respect the RFC
    - improve SECURITY !

    - ... 


