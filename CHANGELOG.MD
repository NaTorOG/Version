# VERSION 6.3
1 - Added new PAPI placeholder %nickyg_chatcolor% which refers to ChatColor of a Player
    ! This new Placeholder can be used in external NickyG chatformat plugins, but will not work for Rainbow Color !
2 - Added better MySQL compatibility for Old MySQL Class drivers

# INSTALLATION FROM PREVIOUS NICKYG VERSIONS
Are you updating nickyg from version < 6.3 ?
If so >
       1 - Shut down your server
       2 - Delete your old NickyG Premium.jar file & config.yml
       2.1 - If you do not want to delete your old config file, just add to your actual config, these values:
       useSSL: false
       verifyServerCertificate: false
       requireSSL: false
       3 - Put in /plugins folder NickyG PREMIUM 6.3

# VERSION 6.2
1 - Removed SkinsRestorer Dependency(You will not need it anymore to let NickyG work) - If you need SKINS features you will need it
2 - Fixed /resetnick 

# INSTALLATION FROM PREVIOUS NICKYG VERSIONS
Are you updating nickyg from version < 6.2 ?
If so >
       1 - Shut down your server
       2 - Delete your old NickyG Premium.jar file
       3 - Put in /plugins folder NickyG PREMIUM 6.2

# VERSION 6.1
1 - Fixed QuitEvent console Error

# INSTALLATION FROM PREVIOUS NICKYG VERSIONS
Are you updating nickyg from version < 6.1 ?
If so >
       1 - Shut down your server
       2 - Delete your old NickyG Premium.jar file
       3 - Put in /plugins folder NickyG PREMIUM 6.1
                     
# VERSION 6.0
1 - Added stats gui features ( /nickstats /nickstats <target> )
2 - Added quickly way to color nicknames ( /colornick & /colornick #hex )
3 - Added new messages and GUI to setup in config.yml
4 - Fixed nickedlist bug
5 - Improved MYSQL Performances

# INSTALLATION FROM PREVIOUS NICKYG VERSIONS
Are you updating nickyg from version < 6.0 ?
If so >
       1 - Shut down your server
       2 - Delete your old NickyG folder and NickyG Premium.jar file
       3 - Put in /plugins folder NickyG PREMIUM 6.0
Are you using MySQL?
You have 2 options > 1) Delete Table 'nicknamesdata' to let NickyG recreate the new one (recommended)
                     2) Create 2 columns in Table 'nicknamesdata' named "CHANGES" , "LASTCHANGE"

# VERSION 5.6
1 - Fixed Console Logger Spam
2 - Fixed exception for MySQL
3 - Added possibility to switch between MySQL Data Sources

# INSTALLATION FROM PREVIOUS NICKYG VERSIONS
Are you updating nickyg from version 5.5?
If so >
       1 - Shut down your server
       2 - Delete your old config.yml and NickyG Premium.jar file
       3 - Put in /plugins folder NickyG PREMIUM 5.6
Are you using MySQL?
Remember to set up the new parameter "mySQLDataSourceClassName"

Are you updating from version older than 5.5?
If so > Follow instruction from version 5.5 installation to 5.6 installation

# VERSION 5.5
1 - Fixed JoinEvent Bug
2 - Fixed ChatFormat % error
3 - Improved ChatFormatter
4 - Added new Permission "nickyg.onlynickcolor" to let users only color their nicknames with /nick <nick>
    With this new permission players will not be able to change nickname, but only to color it
    IMPORTANT: Do not give this permissions to players that already have "nickyg.changenick"
5 - Added a new message in config.yml
 
# INSTALLATION FROM PREVIOUS NICKYG VERSIONS 
Are you updating nickyg from a version older than 5.5?
If so >
       1 - Shut down your server
       2 - Delete your old NickyG folder and NickyG Premium.jar file
       3 - Put in /plugins folder NickyG PREMIUM 5.5
Are you using MySQL?
If so, do not worry, nothing has changed about MySQL DATA.
