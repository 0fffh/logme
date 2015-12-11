login as: ashok
ashok@172.13.10.12's password:
Welcome to Ubuntu 14.04.3 LTS (GNU/Linux 3.19.0-25-generic i686)

 * Documentation:  https://help.ubuntu.com/

  System information as of Sat Dec 12 00:22:47 IST 2015

  System load:  0.97              Processes:             83
  Usage of /:   3.6% of 30.39GB   Users logged in:       0
  Memory usage: 5%                IP address for eth0:   10.0.2.15
  Swap usage:   0%                IP address for virbr0: 192.168.122.1

  Graph this data and manage this system at:
    https://landscape.canonical.com/

Last login: Sat Dec 12 00:22:47 2015
ashok@ubuntulava:~$ sudo apt-get install python-software-properties
[sudo] password for ashok:
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following extra packages will be installed:
  python-pycurl
Suggested packages:
  libcurl4-gnutls-dev python-pycurl-dbg
The following NEW packages will be installed:
  python-pycurl python-software-properties
0 upgraded, 2 newly installed, 0 to remove and 3 not upgraded.
Need to get 66.5 kB of archives.
After this operation, 352 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://us.archive.ubuntu.com/ubuntu/ trusty/main python-pycurl i386 7.19.3                                                                                        -0ubuntu3 [46.9 kB]
Get:2 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/universe python-softwa                                                                                        re-properties all 0.92.37.6 [19.6 kB]
Fetched 66.5 kB in 0s (73.8 kB/s)
Selecting previously unselected package python-pycurl.
(Reading database ... 58285 files and directories currently installed.)
Preparing to unpack .../python-pycurl_7.19.3-0ubuntu3_i386.deb ...
Unpacking python-pycurl (7.19.3-0ubuntu3) ...
Selecting previously unselected package python-software-properties.
Preparing to unpack .../python-software-properties_0.92.37.6_all.deb ...
Unpacking python-software-properties (0.92.37.6) ...
Setting up python-pycurl (7.19.3-0ubuntu3) ...
Setting up python-software-properties (0.92.37.6) ...
ashok@ubuntulava:~$ sudo add-apt-repository ppa:ondrej/php5-oldstable
 This branch follows the oldstable PHP packages as maintained by me & rest of th                                                                                        e Debian pkg-php team.

NOTE: Ubuntu 13.10 (and higher) won't be supported in the repository.  If you re                                                                                        quire PHP 5.4 use Ubuntu 12.04.x LTS.

You can get more information about the packages at https://deb.sury.org

It also includes some widely used PHP modules (if you need some other feel free                                                                                         to send me a request via deb.sury.org or via launchpad).

If you need newest PHP 5.5 you can use the main PHP repository:
    ppa:ondrej/php5

BUGS&FEATURES: This PPA now has a issue tracker: https://deb.sury.org/pages/bugr                                                                                        eporting.html

PLEASE READ: If you like my work and want to give me a little motivation, please                                                                                         consider donating: https://deb.sury.org/pages/donate.html

WARNING: add-apt-repository is broken with non-UTF-8 locales, see https://github                                                                                        .com/oerdnj/deb.sury.org/issues/56 for workaround:

# apt-get install -y language-pack-en-base
# LC_ALL=en_US.UTF-8 add-apt-repository ppa:ondrej/php5-oldstable
 More info: https://launchpad.net/~ondrej/+archive/ubuntu/php5-oldstable
Press [ENTER] to continue or ctrl-c to cancel adding it

gpg: keyring `/tmp/tmpt44rzxba/secring.gpg' created
gpg: keyring `/tmp/tmpt44rzxba/pubring.gpg' created
gpg: requesting key E5267A6C from hkp server keyserver.ubuntu.com
gpg: /tmp/tmpt44rzxba/trustdb.gpg: trustdb created
gpg: key E5267A6C: public key "Launchpad PPA for Ondřej Surý" imported
gpg: Total number processed: 1
gpg:               imported: 1  (RSA: 1)
OK
ashok@ubuntulava:~$ sudo apt-get update
Get:1 http://security.ubuntu.com trusty-security InRelease [64.4 kB]
Ign http://us.archive.ubuntu.com trusty InRelease
Ign http://ppa.launchpad.net trusty InRelease
Get:2 http://security.ubuntu.com trusty-security/main Sources [101 kB]
Get:3 http://ppa.launchpad.net trusty Release.gpg [316 B]
Get:4 http://us.archive.ubuntu.com trusty-updates InRelease [64.4 kB]
Get:5 http://ppa.launchpad.net trusty Release [15.1 kB]
Get:6 http://security.ubuntu.com trusty-security/restricted Sources [4,035 B]
Get:7 http://security.ubuntu.com trusty-security/universe Sources [31.9 kB]
Get:8 http://security.ubuntu.com trusty-security/multiverse Sources [2,353 B]
Get:9 http://security.ubuntu.com trusty-security/main i386 Packages [360 kB]
Get:10 http://ppa.launchpad.net trusty/main i386 Packages [14 B]
Get:11 http://ppa.launchpad.net trusty/main Translation-en [14 B]
Get:12 http://us.archive.ubuntu.com trusty-backports InRelease [64.5 kB]
Get:13 http://us.archive.ubuntu.com trusty Release.gpg [933 B]
Get:14 http://security.ubuntu.com trusty-security/restricted i386 Packages [12.7                                                                                         kB]
Get:15 http://security.ubuntu.com trusty-security/universe i386 Packages [120 kB                                                                                        ]
Get:16 http://us.archive.ubuntu.com trusty-updates/main Sources [247 kB]
Get:17 http://security.ubuntu.com trusty-security/multiverse i386 Packages [4,97                                                                                        2 B]
Get:18 http://security.ubuntu.com trusty-security/main Translation-en [208 kB]
Get:19 http://security.ubuntu.com trusty-security/multiverse Translation-en [2,4                                                                                        37 B]
Get:20 http://security.ubuntu.com trusty-security/restricted Translation-en [3,2                                                                                        06 B]
Get:21 http://security.ubuntu.com trusty-security/universe Translation-en [70.1                                                                                         kB]
Get:22 http://us.archive.ubuntu.com trusty-updates/restricted Sources [5,359 B]
Get:23 http://us.archive.ubuntu.com trusty-updates/universe Sources [145 kB]
Get:24 http://us.archive.ubuntu.com trusty-updates/multiverse Sources [5,167 B]
Get:25 http://us.archive.ubuntu.com trusty-updates/main i386 Packages [644 kB]
Get:26 http://us.archive.ubuntu.com trusty-updates/restricted i386 Packages [15.                                                                                        6 kB]
Get:27 http://us.archive.ubuntu.com trusty-updates/universe i386 Packages [333 k                                                                                        B]
Get:28 http://us.archive.ubuntu.com trusty-updates/multiverse i386 Packages [13.                                                                                        2 kB]
Get:29 http://us.archive.ubuntu.com trusty-updates/main Translation-en [329 kB]
Get:30 http://us.archive.ubuntu.com trusty-updates/multiverse Translation-en [6,                                                                                        832 B]
Get:31 http://us.archive.ubuntu.com trusty-updates/restricted Translation-en [3,                                                                                        699 B]
Get:32 http://us.archive.ubuntu.com trusty-updates/universe Translation-en [174                                                                                         kB]
Get:33 http://us.archive.ubuntu.com trusty-backports/main Sources [8,221 B]
Get:34 http://us.archive.ubuntu.com trusty-backports/restricted Sources [28 B]
Get:35 http://us.archive.ubuntu.com trusty-backports/universe Sources [33.2 kB]
Get:36 http://us.archive.ubuntu.com trusty-backports/multiverse Sources [1,898 B                                                                                        ]
Get:37 http://us.archive.ubuntu.com trusty-backports/main i386 Packages [9,411 B                                                                                        ]
Get:38 http://us.archive.ubuntu.com trusty-backports/restricted i386 Packages [2                                                                                        8 B]
Get:39 http://us.archive.ubuntu.com trusty-backports/universe i386 Packages [39.                                                                                        6 kB]
Get:40 http://us.archive.ubuntu.com trusty-backports/multiverse i386 Packages [1                                                                                        ,552 B]
Get:41 http://us.archive.ubuntu.com trusty-backports/main Translation-en [5,549                                                                                         B]
Get:42 http://us.archive.ubuntu.com trusty-backports/multiverse Translation-en [                                                                                        1,215 B]
Get:43 http://us.archive.ubuntu.com trusty-backports/restricted Translation-en [                                                                                        14 B]
Get:44 http://us.archive.ubuntu.com trusty-backports/universe Translation-en [34                                                                                        .5 kB]
Get:45 http://us.archive.ubuntu.com trusty Release [58.5 kB]
Get:46 http://us.archive.ubuntu.com trusty/main Sources [1,064 kB]
Get:47 http://us.archive.ubuntu.com trusty/restricted Sources [5,433 B]
Get:48 http://us.archive.ubuntu.com trusty/universe Sources [6,399 kB]
Get:49 http://us.archive.ubuntu.com trusty/multiverse Sources [174 kB]
Get:50 http://us.archive.ubuntu.com trusty/main i386 Packages [1,348 kB]
Get:51 http://us.archive.ubuntu.com trusty/restricted i386 Packages [13.4 kB]
Get:52 http://us.archive.ubuntu.com trusty/universe i386 Packages [5,866 kB]
Get:53 http://us.archive.ubuntu.com trusty/multiverse i386 Packages [134 kB]
Get:54 http://us.archive.ubuntu.com trusty/main Translation-en [762 kB]
Get:55 http://us.archive.ubuntu.com trusty/multiverse Translation-en [102 kB]
Get:56 http://us.archive.ubuntu.com trusty/restricted Translation-en [3,457 B]
Get:57 http://us.archive.ubuntu.com trusty/universe Translation-en [4,089 kB]
Ign http://us.archive.ubuntu.com trusty/main Translation-en_US
Ign http://us.archive.ubuntu.com trusty/multiverse Translation-en_US
Ign http://us.archive.ubuntu.com trusty/restricted Translation-en_US
Ign http://us.archive.ubuntu.com trusty/universe Translation-en_US
Fetched 23.2 MB in 1min 7s (346 kB/s)
Reading package lists... Done
ashok@ubuntulava:~$ sudo apt-cache policy php5
php5:
  Installed: (none)
  Candidate: 5.5.9+dfsg-1ubuntu4.14
  Version table:
     5.5.9+dfsg-1ubuntu4.14 0
        500 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main i386 Packag                                                                                        es
        500 http://security.ubuntu.com/ubuntu/ trusty-security/main i386 Package                                                                                        s
     5.5.9+dfsg-1ubuntu4 0
        500 http://us.archive.ubuntu.com/ubuntu/ trusty/main i386 Packages
ashok@ubuntulava:~$ sudo apt-cache policy php5.5.9
N: Unable to locate package php5.5.9
N: Couldn't find any package by regex 'php5.5.9'
ashok@ubuntulava:~$ sudo apt-cache policy php>=5*
ashok@ubuntulava:~$ sudo apt-cache policy php >= 5.5.9
ashok@ubuntulava:~$ sudo apt-cache policy php >=5.5.9
ashok@ubuntulava:~$ sudo apt-get install apache2
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following extra packages will be installed:
  apache2-bin apache2-data libapr1 libaprutil1 libaprutil1-dbd-sqlite3
  libaprutil1-ldap ssl-cert
Suggested packages:
  apache2-doc apache2-suexec-pristine apache2-suexec-custom apache2-utils
  openssl-blacklist
The following NEW packages will be installed:
  apache2 apache2-bin apache2-data libapr1 libaprutil1 libaprutil1-dbd-sqlite3
  libaprutil1-ldap ssl-cert
0 upgraded, 8 newly installed, 0 to remove and 3 not upgraded.
Need to get 1,271 kB of archives.
After this operation, 5,057 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://us.archive.ubuntu.com/ubuntu/ trusty/main libapr1 i386 1.5.0-1 [88.                                                                                        8 kB]
Get:2 http://us.archive.ubuntu.com/ubuntu/ trusty/main libaprutil1 i386 1.5.3-1                                                                                         [76.6 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu/ trusty/main libaprutil1-dbd-sqlite3 i                                                                                        386 1.5.3-1 [10.3 kB]
Get:4 http://us.archive.ubuntu.com/ubuntu/ trusty/main libaprutil1-ldap i386 1.5                                                                                        .3-1 [8,552 B]
Get:5 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main apache2-bin i386                                                                                         2.4.7-1ubuntu4.8 [823 kB]
Get:6 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main apache2-data all                                                                                         2.4.7-1ubuntu4.8 [160 kB]
Get:7 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main apache2 i386 2.4.                                                                                        7-1ubuntu4.8 [87.6 kB]
Get:8 http://us.archive.ubuntu.com/ubuntu/ trusty/main ssl-cert all 1.0.33 [16.6                                                                                         kB]
Fetched 1,271 kB in 5s (217 kB/s)
Preconfiguring packages ...
Selecting previously unselected package libapr1:i386.
(Reading database ... 58328 files and directories currently installed.)
Preparing to unpack .../libapr1_1.5.0-1_i386.deb ...
Unpacking libapr1:i386 (1.5.0-1) ...
Selecting previously unselected package libaprutil1:i386.
Preparing to unpack .../libaprutil1_1.5.3-1_i386.deb ...
Unpacking libaprutil1:i386 (1.5.3-1) ...
Selecting previously unselected package libaprutil1-dbd-sqlite3:i386.
Preparing to unpack .../libaprutil1-dbd-sqlite3_1.5.3-1_i386.deb ...
Unpacking libaprutil1-dbd-sqlite3:i386 (1.5.3-1) ...
Selecting previously unselected package libaprutil1-ldap:i386.
Preparing to unpack .../libaprutil1-ldap_1.5.3-1_i386.deb ...
Unpacking libaprutil1-ldap:i386 (1.5.3-1) ...
Selecting previously unselected package apache2-bin.
Preparing to unpack .../apache2-bin_2.4.7-1ubuntu4.8_i386.deb ...
Unpacking apache2-bin (2.4.7-1ubuntu4.8) ...
Selecting previously unselected package apache2-data.
Preparing to unpack .../apache2-data_2.4.7-1ubuntu4.8_all.deb ...
Unpacking apache2-data (2.4.7-1ubuntu4.8) ...
Selecting previously unselected package apache2.
Preparing to unpack .../apache2_2.4.7-1ubuntu4.8_i386.deb ...
Unpacking apache2 (2.4.7-1ubuntu4.8) ...
Selecting previously unselected package ssl-cert.
Preparing to unpack .../ssl-cert_1.0.33_all.deb ...
Unpacking ssl-cert (1.0.33) ...
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
Processing triggers for ureadahead (0.100.0-16) ...
ureadahead will be reprofiled on next reboot
Processing triggers for ufw (0.34~rc-0ubuntu2) ...
Setting up libapr1:i386 (1.5.0-1) ...
Setting up libaprutil1:i386 (1.5.3-1) ...
Setting up libaprutil1-dbd-sqlite3:i386 (1.5.3-1) ...
Setting up libaprutil1-ldap:i386 (1.5.3-1) ...
Setting up apache2-bin (2.4.7-1ubuntu4.8) ...
Setting up apache2-data (2.4.7-1ubuntu4.8) ...
Setting up apache2 (2.4.7-1ubuntu4.8) ...
Enabling module mpm_event.
Enabling module authz_core.
Enabling module authz_host.
Enabling module authn_core.
Enabling module auth_basic.
Enabling module access_compat.
Enabling module authn_file.
Enabling module authz_user.
Enabling module alias.
Enabling module dir.
Enabling module autoindex.
Enabling module env.
Enabling module mime.
Enabling module negotiation.
Enabling module setenvif.
Enabling module filter.
Enabling module deflate.
Enabling module status.
Enabling conf charset.
Enabling conf localized-error-pages.
Enabling conf other-vhosts-access-log.
Enabling conf security.
Enabling conf serve-cgi-bin.
Enabling site 000-default.
 * Starting web server apache2                                                                                                                                          AH00558: apache2: Could not reliably determine the server's fully qualified doma                                                                                        in name, using 127.0.1.1. Set the 'ServerName' directive globally to suppress th                                                                                        is message
 *
Setting up ssl-cert (1.0.33) ...
Processing triggers for libc-bin (2.19-0ubuntu6.6) ...
Processing triggers for ureadahead (0.100.0-16) ...
Processing triggers for ufw (0.34~rc-0ubuntu2) ...
ashok@ubuntulava:~$ sudo apt-get install php5
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following extra packages will be installed:
  libapache2-mod-php5 php5-cli php5-common php5-json php5-readline
Suggested packages:
  php-pear php5-user-cache
The following NEW packages will be installed:
  libapache2-mod-php5 php5 php5-cli php5-common php5-json php5-readline
0 upgraded, 6 newly installed, 0 to remove and 3 not upgraded.
Need to get 4,793 kB of archives.
After this operation, 19.7 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://us.archive.ubuntu.com/ubuntu/ trusty/main php5-json i386 1.3.2-2bui                                                                                        ld1 [34.2 kB]
Get:2 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main php5-common i386                                                                                         5.5.9+dfsg-1ubuntu4.14 [445 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main php5-cli i386 5.5                                                                                        .9+dfsg-1ubuntu4.14 [2,157 kB]
Get:4 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main php5-readline i38                                                                                        6 5.5.9+dfsg-1ubuntu4.14 [11.8 kB]
Get:5 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main libapache2-mod-ph                                                                                        p5 i386 5.5.9+dfsg-1ubuntu4.14 [2,144 kB]
Get:6 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main php5 all 5.5.9+df                                                                                        sg-1ubuntu4.14 [1,300 B]
Fetched 4,793 kB in 12s (399 kB/s)
Selecting previously unselected package php5-json.
(Reading database ... 58971 files and directories currently installed.)
Preparing to unpack .../php5-json_1.3.2-2build1_i386.deb ...
Unpacking php5-json (1.3.2-2build1) ...
Selecting previously unselected package php5-common.
Preparing to unpack .../php5-common_5.5.9+dfsg-1ubuntu4.14_i386.deb ...
Unpacking php5-common (5.5.9+dfsg-1ubuntu4.14) ...
Selecting previously unselected package php5-cli.
Preparing to unpack .../php5-cli_5.5.9+dfsg-1ubuntu4.14_i386.deb ...
Unpacking php5-cli (5.5.9+dfsg-1ubuntu4.14) ...
Selecting previously unselected package php5-readline.
Preparing to unpack .../php5-readline_5.5.9+dfsg-1ubuntu4.14_i386.deb ...
Unpacking php5-readline (5.5.9+dfsg-1ubuntu4.14) ...
Selecting previously unselected package libapache2-mod-php5.
Preparing to unpack .../libapache2-mod-php5_5.5.9+dfsg-1ubuntu4.14_i386.deb ...
Unpacking libapache2-mod-php5 (5.5.9+dfsg-1ubuntu4.14) ...
Selecting previously unselected package php5.
Preparing to unpack .../php5_5.5.9+dfsg-1ubuntu4.14_all.deb ...
Unpacking php5 (5.5.9+dfsg-1ubuntu4.14) ...
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
Setting up php5-json (1.3.2-2build1) ...
php5_invoke: Enable module json for cli SAPI
php5_invoke: Enable module json for apache2 SAPI
Setting up php5-common (5.5.9+dfsg-1ubuntu4.14) ...

Creating config file /etc/php5/mods-available/pdo.ini with new version
php5_invoke: Enable module pdo for cli SAPI
php5_invoke: Enable module pdo for apache2 SAPI

Creating config file /etc/php5/mods-available/opcache.ini with new version
php5_invoke: Enable module opcache for cli SAPI
php5_invoke: Enable module opcache for apache2 SAPI
Setting up php5-cli (5.5.9+dfsg-1ubuntu4.14) ...
update-alternatives: using /usr/bin/php5 to provide /usr/bin/php (php) in auto m                                                                                        ode

Creating config file /etc/php5/cli/php.ini with new version
php5_invoke opcache: already enabled for cli SAPI
php5_invoke json: already enabled for cli SAPI
php5_invoke pdo: already enabled for cli SAPI
Setting up php5-readline (5.5.9+dfsg-1ubuntu4.14) ...

Creating config file /etc/php5/mods-available/readline.ini with new version
php5_invoke: Enable module readline for cli SAPI
php5_invoke: Enable module readline for apache2 SAPI
Setting up libapache2-mod-php5 (5.5.9+dfsg-1ubuntu4.14) ...

Creating config file /etc/php5/apache2/php.ini with new version
php5_invoke opcache: already enabled for apache2 SAPI
php5_invoke json: already enabled for apache2 SAPI
php5_invoke readline: already enabled for apache2 SAPI
php5_invoke pdo: already enabled for apache2 SAPI
Module mpm_event disabled.
Enabling module mpm_prefork.
apache2_switch_mpm Switch to prefork
 * Restarting web server apache2                                                                                                                                        AH00558: apache2: Could not reliably determine the server's fully qualified doma                                                                                        in name, using 127.0.1.1. Set the 'ServerName' directive globally to suppress th                                                                                        is message
                                                                         [ OK ]
apache2_invoke: Enable module php5
 * Restarting web server apache2                                                                                                                                        AH00558: apache2: Could not reliably determine the server's fully qualified doma                                                                                        in name, using 127.0.1.1. Set the 'ServerName' directive globally to suppress th                                                                                        is message
                                                                         [ OK ]
Setting up php5 (5.5.9+dfsg-1ubuntu4.14) ...
ashok@ubuntulava:~$ sudo apt-get install mysql-server
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following extra packages will be installed:
  libdbd-mysql-perl libdbi-perl libhtml-template-perl libmysqlclient18
  libterm-readkey-perl mysql-client-5.5 mysql-client-core-5.5 mysql-common
  mysql-server-5.5 mysql-server-core-5.5
Suggested packages:
  libclone-perl libmldbm-perl libnet-daemon-perl libplrpc-perl
  libsql-statement-perl libipc-sharedcache-perl tinyca mailx
The following NEW packages will be installed:
  libdbd-mysql-perl libdbi-perl libhtml-template-perl libmysqlclient18
  libterm-readkey-perl mysql-client-5.5 mysql-client-core-5.5 mysql-common
  mysql-server mysql-server-5.5 mysql-server-core-5.5
0 upgraded, 11 newly installed, 0 to remove and 3 not upgraded.
Need to get 9,102 kB of archives.
After this operation, 93.8 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main mysql-common all                                                                                         5.5.46-0ubuntu0.14.04.2 [14.1 kB]
Get:2 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main libmysqlclient18                                                                                         i386 5.5.46-0ubuntu0.14.04.2 [596 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu/ trusty/main libdbi-perl i386 1.630-1                                                                                         [881 kB]
Get:4 http://us.archive.ubuntu.com/ubuntu/ trusty/main libdbd-mysql-perl i386 4.                                                                                        025-1 [99.6 kB]
Get:5 http://us.archive.ubuntu.com/ubuntu/ trusty/main libterm-readkey-perl i386                                                                                         2.31-1 [27.2 kB]
Get:6 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main mysql-client-core                                                                                        -5.5 i386 5.5.46-0ubuntu0.14.04.2 [704 kB]
Get:7 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main mysql-client-5.5                                                                                         i386 5.5.46-0ubuntu0.14.04.2 [1,558 kB]
Get:8 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main mysql-server-core                                                                                        -5.5 i386 5.5.46-0ubuntu0.14.04.2 [3,388 kB]
Get:9 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main mysql-server-5.5                                                                                         i386 5.5.46-0ubuntu0.14.04.2 [1,756 kB]
Get:10 http://us.archive.ubuntu.com/ubuntu/ trusty/main libhtml-template-perl al                                                                                        l 2.95-1 [65.5 kB]
Get:11 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main mysql-server all                                                                                         5.5.46-0ubuntu0.14.04.2 [12.4 kB]
Fetched 9,102 kB in 14s (626 kB/s)
Preconfiguring packages ...
Selecting previously unselected package mysql-common.
(Reading database ... 59059 files and directories currently installed.)
Preparing to unpack .../mysql-common_5.5.46-0ubuntu0.14.04.2_all.deb ...
Unpacking mysql-common (5.5.46-0ubuntu0.14.04.2) ...
Selecting previously unselected package libmysqlclient18:i386.
Preparing to unpack .../libmysqlclient18_5.5.46-0ubuntu0.14.04.2_i386.deb ...
Unpacking libmysqlclient18:i386 (5.5.46-0ubuntu0.14.04.2) ...
Selecting previously unselected package libdbi-perl.
Preparing to unpack .../libdbi-perl_1.630-1_i386.deb ...
Unpacking libdbi-perl (1.630-1) ...
Selecting previously unselected package libdbd-mysql-perl.
Preparing to unpack .../libdbd-mysql-perl_4.025-1_i386.deb ...
Unpacking libdbd-mysql-perl (4.025-1) ...
Selecting previously unselected package libterm-readkey-perl.
Preparing to unpack .../libterm-readkey-perl_2.31-1_i386.deb ...
Unpacking libterm-readkey-perl (2.31-1) ...
Selecting previously unselected package mysql-client-core-5.5.
Preparing to unpack .../mysql-client-core-5.5_5.5.46-0ubuntu0.14.04.2_i386.deb .                                                                                        ..
Unpacking mysql-client-core-5.5 (5.5.46-0ubuntu0.14.04.2) ...
Selecting previously unselected package mysql-client-5.5.
Preparing to unpack .../mysql-client-5.5_5.5.46-0ubuntu0.14.04.2_i386.deb ...
Unpacking mysql-client-5.5 (5.5.46-0ubuntu0.14.04.2) ...
Selecting previously unselected package mysql-server-core-5.5.
Preparing to unpack .../mysql-server-core-5.5_5.5.46-0ubuntu0.14.04.2_i386.deb .                                                                                        ..
Unpacking mysql-server-core-5.5 (5.5.46-0ubuntu0.14.04.2) ...
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
Setting up mysql-common (5.5.46-0ubuntu0.14.04.2) ...
Selecting previously unselected package mysql-server-5.5.
(Reading database ... 59415 files and directories currently installed.)
Preparing to unpack .../mysql-server-5.5_5.5.46-0ubuntu0.14.04.2_i386.deb ...
Unpacking mysql-server-5.5 (5.5.46-0ubuntu0.14.04.2) ...
Selecting previously unselected package libhtml-template-perl.
Preparing to unpack .../libhtml-template-perl_2.95-1_all.deb ...
Unpacking libhtml-template-perl (2.95-1) ...
Selecting previously unselected package mysql-server.
Preparing to unpack .../mysql-server_5.5.46-0ubuntu0.14.04.2_all.deb ...
Unpacking mysql-server (5.5.46-0ubuntu0.14.04.2) ...
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
Processing triggers for ureadahead (0.100.0-16) ...
Setting up libmysqlclient18:i386 (5.5.46-0ubuntu0.14.04.2) ...
Setting up libdbi-perl (1.630-1) ...
Setting up libdbd-mysql-perl (4.025-1) ...
Setting up libterm-readkey-perl (2.31-1) ...
Setting up mysql-client-core-5.5 (5.5.46-0ubuntu0.14.04.2) ...
Setting up mysql-client-5.5 (5.5.46-0ubuntu0.14.04.2) ...
Setting up mysql-server-core-5.5 (5.5.46-0ubuntu0.14.04.2) ...
Setting up mysql-server-5.5 (5.5.46-0ubuntu0.14.04.2) ...
151212  0:34:01 [Warning] Using unique option prefix key_buffer instead of key_b                                                                                        uffer_size is deprecated and will be removed in a future release. Please use the                                                                                         full name instead.
151212  0:34:01 [Note] /usr/sbin/mysqld (mysqld 5.5.46-0ubuntu0.14.04.2) startin                                                                                        g as process 5406 ...
mysql start/running, process 5538
Setting up libhtml-template-perl (2.95-1) ...
Processing triggers for ureadahead (0.100.0-16) ...
Setting up mysql-server (5.5.46-0ubuntu0.14.04.2) ...
Processing triggers for libc-bin (2.19-0ubuntu6.6) ...
ashok@ubuntulava:~$ sudo apt-get install php5-mysql
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following NEW packages will be installed:
  php5-mysql
0 upgraded, 1 newly installed, 0 to remove and 3 not upgraded.
Need to get 59.7 kB of archives.
After this operation, 264 kB of additional disk space will be used.
Get:1 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main php5-mysql i386 5                                                                                        .5.9+dfsg-1ubuntu4.14 [59.7 kB]
Fetched 59.7 kB in 1s (47.5 kB/s)
Selecting previously unselected package php5-mysql.
(Reading database ... 59517 files and directories currently installed.)
Preparing to unpack .../php5-mysql_5.5.9+dfsg-1ubuntu4.14_i386.deb ...
Unpacking php5-mysql (5.5.9+dfsg-1ubuntu4.14) ...
Processing triggers for libapache2-mod-php5 (5.5.9+dfsg-1ubuntu4.14) ...
Setting up php5-mysql (5.5.9+dfsg-1ubuntu4.14) ...

Creating config file /etc/php5/mods-available/mysql.ini with new version
php5_invoke: Enable module mysql for cli SAPI
php5_invoke: Enable module mysql for apache2 SAPI

Creating config file /etc/php5/mods-available/mysqli.ini with new version
php5_invoke: Enable module mysqli for cli SAPI
php5_invoke: Enable module mysqli for apache2 SAPI

Creating config file /etc/php5/mods-available/pdo_mysql.ini with new version
php5_invoke: Enable module pdo_mysql for cli SAPI
php5_invoke: Enable module pdo_mysql for apache2 SAPI
Processing triggers for libapache2-mod-php5 (5.5.9+dfsg-1ubuntu4.14) ...
ashok@ubuntulava:~$ php -v
PHP 5.5.9-1ubuntu4.14 (cli) (built: Oct 28 2015 01:32:13)
Copyright (c) 1997-2014 The PHP Group
Zend Engine v2.5.0, Copyright (c) 1998-2014 Zend Technologies
    with Zend OPcache v7.0.3, Copyright (c) 1999-2014, by Zend Technologies
ashok@ubuntulava:~$ apache2 -v
Server version: Apache/2.4.7 (Ubuntu)
Server built:   Oct 14 2015 14:18:49
ashok@ubuntulava:~$ sudo apt-get install unzip
Reading package lists... Done
Building dependency tree
Reading state information... Done
Suggested packages:
  zip
The following NEW packages will be installed:
  unzip
0 upgraded, 1 newly installed, 0 to remove and 3 not upgraded.
Need to get 150 kB of archives.
After this operation, 388 kB of additional disk space will be used.
Get:1 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main unzip i386 6.0-9u                                                                                        buntu1.5 [150 kB]
Fetched 150 kB in 1s (96.5 kB/s)
Selecting previously unselected package unzip.
(Reading database ... 59528 files and directories currently installed.)
Preparing to unpack .../unzip_6.0-9ubuntu1.5_i386.deb ...
Unpacking unzip (6.0-9ubuntu1.5) ...
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
Processing triggers for mime-support (3.54ubuntu1.1) ...
Setting up unzip (6.0-9ubuntu1.5) ...
ashok@ubuntulava:~$ sudo apt-get install curl
Reading package lists... Done
Building dependency tree
Reading state information... Done
curl is already the newest version.
0 upgraded, 0 newly installed, 0 to remove and 3 not upgraded.
ashok@ubuntulava:~$ sudo apt-get install openssl
Reading package lists... Done
Building dependency tree
Reading state information... Done
openssl is already the newest version.
0 upgraded, 0 newly installed, 0 to remove and 3 not upgraded.
ashok@ubuntulava:~$ sudo apt-get install php5-mcrypt
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following extra packages will be installed:
  libmcrypt4
Suggested packages:
  libmcrypt-dev mcrypt
The following NEW packages will be installed:
  libmcrypt4 php5-mcrypt
0 upgraded, 2 newly installed, 0 to remove and 3 not upgraded.
Need to get 76.0 kB of archives.
After this operation, 301 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://us.archive.ubuntu.com/ubuntu/ trusty/universe libmcrypt4 i386 2.5.8                                                                                        -3.1ubuntu1 [61.1 kB]
Get:2 http://us.archive.ubuntu.com/ubuntu/ trusty/universe php5-mcrypt i386 5.4.                                                                                        6-0ubuntu5 [14.9 kB]
Fetched 76.0 kB in 1s (62.2 kB/s)
Selecting previously unselected package libmcrypt4.
(Reading database ... 59546 files and directories currently installed.)
Preparing to unpack .../libmcrypt4_2.5.8-3.1ubuntu1_i386.deb ...
Unpacking libmcrypt4 (2.5.8-3.1ubuntu1) ...
Selecting previously unselected package php5-mcrypt.
Preparing to unpack .../php5-mcrypt_5.4.6-0ubuntu5_i386.deb ...
Unpacking php5-mcrypt (5.4.6-0ubuntu5) ...
Setting up libmcrypt4 (2.5.8-3.1ubuntu1) ...
Setting up php5-mcrypt (5.4.6-0ubuntu5) ...
Processing triggers for libc-bin (2.19-0ubuntu6.6) ...
ashok@ubuntulava:~$ curl -sS https://getcomposer.org/installer | php
#!/usr/bin/env php
All settings correct for using Composer
Downloading...

Composer successfully installed to: /home/ashok/composer.phar
Use it: php composer.phar
ashok@ubuntulava:~$ sudo mv composer.phar /usr/local/bin/composer
ashok@ubuntulava:~$ sudo a2enmod rewrite
Enabling module rewrite.
To activate the new configuration, you need to run:
  service apache2 restart
ashok@ubuntulava:~$ service apache2 restart
 * Restarting web server apache2                                         [fail]
ashok@ubuntulava:~$ sudo service apache2 restart
 * Restarting web server apache2                                                                                                                                        AH00558: apache2: Could not reliably determine the server's fully qualified doma                                                                                        in name, using 127.0.1.1. Set the 'ServerName' directive globally to suppress th                                                                                        is message
                                                                         [ OK ]
ashok@ubuntulava:~$ sudo nano /etc/apache2/sites-available/default
ashok@ubuntulava:~$ cd /etc/apache2/sites-available/default
-bash: cd: /etc/apache2/sites-available/default: No such file or directory
ashok@ubuntulava:~$ cd ..
ashok@ubuntulava:/home$ cd /etc/apache2/sites-available/default
-bash: cd: /etc/apache2/sites-available/default: No such file or directory
ashok@ubuntulava:/home$ sudo nano /etc/apache2/sites-available/default
ashok@ubuntulava:/home$ cd  /etc/apache2/sites-available/
ashok@ubuntulava:/etc/apache2/sites-available$ ls
000-default.conf  default-ssl.conf
ashok@ubuntulava:/etc/apache2/sites-available$ ls -la
total 20
drwxr-xr-x 2 root root 4096 Dec 12 00:32 .
drwxr-xr-x 8 root root 4096 Dec 12 00:32 ..
-rw-r--r-- 1 root root 1332 Jan  7  2014 000-default.conf
-rw-r--r-- 1 root root 6437 Jan  7  2014 default-ssl.conf
ashok@ubuntulava:/etc/apache2/sites-available$ ls
000-default.conf  default-ssl.conf
ashok@ubuntulava:/etc/apache2/sites-available$ nano 000-default.conf
ashok@ubuntulava:/etc/apache2/sites-available$ cd ..
ashok@ubuntulava:/etc/apache2$ ls
apache2.conf    conf-enabled  magic           mods-enabled  sites-available
conf-available  envvars       mods-available  ports.conf    sites-enabled
ashok@ubuntulava:/etc/apache2$ cd sites-available/
ashok@ubuntulava:/etc/apache2/sites-available$ ls
000-default.conf  default-ssl.conf
ashok@ubuntulava:/etc/apache2/sites-available$ cd ..
ashok@ubuntulava:/etc/apache2$ cd ..
ashok@ubuntulava:/etc$ cd apache2/
ashok@ubuntulava:/etc/apache2$ ls
apache2.conf    conf-enabled  magic           mods-enabled  sites-available
conf-available  envvars       mods-available  ports.conf    sites-enabled
ashok@ubuntulava:/etc/apache2$ ifconfig
eth0      Link encap:Ethernet  HWaddr 08:00:27:17:d9:2a
          inet addr:10.0.2.15  Bcast:10.0.2.255  Mask:255.255.255.0
          inet6 addr: fe80::a00:27ff:fe17:d92a/64 Scope:Link
          UP BROADCAST RUNNING MULTICAST  MTU:1500  Metric:1
          RX packets:35638 errors:0 dropped:0 overruns:0 frame:0
          TX packets:8421 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:1000
          RX bytes:41256191 (41.2 MB)  TX bytes:531805 (531.8 KB)

eth1      Link encap:Ethernet  HWaddr 08:00:27:72:62:cf
          inet addr:172.13.10.12  Bcast:172.13.10.255  Mask:255.255.255.0
          inet6 addr: fe80::a00:27ff:fe72:62cf/64 Scope:Link
          UP BROADCAST RUNNING MULTICAST  MTU:1500  Metric:1
          RX packets:1909 errors:0 dropped:0 overruns:0 frame:0
          TX packets:2175 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:1000
          RX bytes:156552 (156.5 KB)  TX bytes:353153 (353.1 KB)

lo        Link encap:Local Loopback
          inet addr:127.0.0.1  Mask:255.0.0.0
          inet6 addr: ::1/128 Scope:Host
          UP LOOPBACK RUNNING  MTU:65536  Metric:1
          RX packets:0 errors:0 dropped:0 overruns:0 frame:0
          TX packets:0 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:0
          RX bytes:0 (0.0 B)  TX bytes:0 (0.0 B)

virbr0    Link encap:Ethernet  HWaddr ae:4e:2e:85:12:ee
          inet addr:192.168.122.1  Bcast:192.168.122.255  Mask:255.255.255.0
          UP BROADCAST MULTICAST  MTU:1500  Metric:1
          RX packets:0 errors:0 dropped:0 overruns:0 frame:0
          TX packets:0 errors:0 dropped:0 overruns:0 carrier:0
          collisions:0 txqueuelen:0
          RX bytes:0 (0.0 B)  TX bytes:0 (0.0 B)

ashok@ubuntulava:/etc/apache2$ ^C
ashok@ubuntulava:/etc/apache2$ nano /etc/apache2/apache2.conf
ashok@ubuntulava:/etc/apache2$ cd ..
ashok@ubuntulava:/etc$ cd ..
ashok@ubuntulava:/$ cd ..
ashok@ubuntulava:/$ cd -P
ashok@ubuntulava:~$ mkdir
mkdir: missing operand
Try 'mkdir --help' for more information.
ashok@ubuntulava:~$ mkdir lavas
ashok@ubuntulava:~$ pwd
/home/ashok
ashok@ubuntulava:~$ mkdir lava
ashok@ubuntulava:~$ cd lava
ashok@ubuntulava:~/lava$ ls
ashok@ubuntulava:~/lava$ cd cd /var/www
-bash: cd: cd: No such file or directory
ashok@ubuntulava:~/lava$ cd /var/www
ashok@ubuntulava:/var/www$ cd html/
ashok@ubuntulava:/var/www/html$ ls
index.html
ashok@ubuntulava:/var/www/html$ cd ..
ashok@ubuntulava:/var/www$ ls
html
ashok@ubuntulava:/var/www$ mkdir lavasite
mkdir: cannot create directory ‘lavasite’: Permission denied
ashok@ubuntulava:/var/www$ sudo mkdir lavasite
ashok@ubuntulava:/var/www$ ls
html  lavasite
ashok@ubuntulava:/var/www$ cp html lavasite/
cp: omitting directory ‘html’
ashok@ubuntulava:/var/www$ cd lavasite/
ashok@ubuntulava:/var/www/lavasite$ ls
ashok@ubuntulava:/var/www/lavasite$ cd ..
ashok@ubuntulava:/var/www$ cd html/
ashok@ubuntulava:/var/www/html$ ls
index.html
ashok@ubuntulava:/var/www/html$ cd ..
ashok@ubuntulava:/var/www$ cp html/index.html  lavasite
cp: cannot create regular file ‘lavasite/index.html’: Permission denied
ashok@ubuntulava:/var/www$ sudo cp html/index.html  lavasite
ashok@ubuntulava:/var/www$ ls
html  lavasite
ashok@ubuntulava:/var/www$ cd lavasite/
ashok@ubuntulava:/var/www/lavasite$ ls
index.html
ashok@ubuntulava:/var/www/lavasite$ ^C
ashok@ubuntulava:/var/www/lavasite$ cd ..
ashok@ubuntulava:/var/www$ ls
html  lavasite
ashok@ubuntulava:/var/www$ cd html/
ashok@ubuntulava:/var/www/html$ ls
index.html
ashok@ubuntulava:/var/www/html$ sudo mkdir hellox
ashok@ubuntulava:/var/www/html$ cp index.html hellox/
cp: cannot create regular file ‘hellox/index.html’: Permission denied
ashok@ubuntulava:/var/www/html$ sudo cp index.html hellox/
ashok@ubuntulava:/var/www/html$ mkdir lvr
mkdir: cannot create directory ‘lvr’: Permission denied
ashok@ubuntulava:/var/www/html$ sudo mkdir lvr
ashok@ubuntulava:/var/www/html$ cd lvr/
ashok@ubuntulava:/var/www/html/lvr$ wget https://github.com/laravel/laravel/arch                                                                                        ive/master.zip
--2015-12-12 00:52:23--  https://github.com/laravel/laravel/archive/master.zip
Resolving github.com (github.com)... 192.30.252.130
Connecting to github.com (github.com)|192.30.252.130|:443... connected.
HTTP request sent, awaiting response... 302 Found
Location: https://codeload.github.com/laravel/laravel/zip/master [following]
--2015-12-12 00:52:24--  https://codeload.github.com/laravel/laravel/zip/master
Resolving codeload.github.com (codeload.github.com)... 192.30.252.145
Connecting to codeload.github.com (codeload.github.com)|192.30.252.145|:443... c                                                                                        onnected.
HTTP request sent, awaiting response... 200 OK
Length: 45643 (45K) [application/zip]
master.zip: Permission denied

Cannot write to ‘master.zip’ (Success).
ashok@ubuntulava:/var/www/html/lvr$ unzip master.zip && cd laravel-master/ && mv                                                                                         * ../ && cd ..
unzip:  cannot find or open master.zip, master.zip.zip or master.zip.ZIP.
ashok@ubuntulava:/var/www/html/lvr$ rm -r laravel-master && rm master.zip
rm: cannot remove ‘laravel-master’: No such file or directory
ashok@ubuntulava:/var/www/html/lvr$ ls
ashok@ubuntulava:/var/www/html/lvr$ wget https://github.com/laravel/laravel/arch                                                                                        ive/master.zip
--2015-12-12 00:52:50--  https://github.com/laravel/laravel/archive/master.zip
Resolving github.com (github.com)... 192.30.252.131
Connecting to github.com (github.com)|192.30.252.131|:443... connected.
HTTP request sent, awaiting response... 302 Found
Location: https://codeload.github.com/laravel/laravel/zip/master [following]
--2015-12-12 00:52:51--  https://codeload.github.com/laravel/laravel/zip/master
Resolving codeload.github.com (codeload.github.com)... 192.30.252.145
Connecting to codeload.github.com (codeload.github.com)|192.30.252.145|:443... c                                                                                        onnected.
HTTP request sent, awaiting response... 200 OK
Length: 45643 (45K) [application/zip]
master.zip: Permission denied

Cannot write to ‘master.zip’ (Success).
ashok@ubuntulava:/var/www/html/lvr$ sudo wget https://github.com/laravel/laravel                                                                                        /archive/master.zip
--2015-12-12 00:53:03--  https://github.com/laravel/laravel/archive/master.zip
Resolving github.com (github.com)... 192.30.252.131
Connecting to github.com (github.com)|192.30.252.131|:443... connected.
HTTP request sent, awaiting response... 302 Found
Location: https://codeload.github.com/laravel/laravel/zip/master [following]
--2015-12-12 00:53:05--  https://codeload.github.com/laravel/laravel/zip/master
Resolving codeload.github.com (codeload.github.com)... 192.30.252.145
Connecting to codeload.github.com (codeload.github.com)|192.30.252.145|:443... c                                                                                        onnected.
HTTP request sent, awaiting response... 200 OK
Length: 45643 (45K) [application/zip]
Saving to: ‘master.zip’

100%[======================================>] 45,643      30.8KB/s   in 1.4s

2015-12-12 00:53:12 (30.8 KB/s) - ‘master.zip’ saved [45643/45643]

ashok@ubuntulava:/var/www/html/lvr$ ls
master.zip
ashok@ubuntulava:/var/www/html/lvr$ sudo unzip master.zip && cd laravel-master/                                                                                         && mv * ../ && cd ..
Archive:  master.zip
8c27cb56d0603938691107094eb70cbba2907c88
   creating: laravel-master/
  inflating: laravel-master/.env.example
  inflating: laravel-master/.gitattributes
  inflating: laravel-master/.gitignore
   creating: laravel-master/app/
   creating: laravel-master/app/Console/
   creating: laravel-master/app/Console/Commands/
  inflating: laravel-master/app/Console/Commands/Inspire.php
  inflating: laravel-master/app/Console/Kernel.php
   creating: laravel-master/app/Events/
  inflating: laravel-master/app/Events/Event.php
   creating: laravel-master/app/Exceptions/
  inflating: laravel-master/app/Exceptions/Handler.php
   creating: laravel-master/app/Http/
   creating: laravel-master/app/Http/Controllers/
   creating: laravel-master/app/Http/Controllers/Auth/
  inflating: laravel-master/app/Http/Controllers/Auth/AuthController.php
  inflating: laravel-master/app/Http/Controllers/Auth/PasswordController.php
  inflating: laravel-master/app/Http/Controllers/Controller.php
  inflating: laravel-master/app/Http/Kernel.php
   creating: laravel-master/app/Http/Middleware/
  inflating: laravel-master/app/Http/Middleware/Authenticate.php
  inflating: laravel-master/app/Http/Middleware/EncryptCookies.php
  inflating: laravel-master/app/Http/Middleware/RedirectIfAuthenticated.php
  inflating: laravel-master/app/Http/Middleware/VerifyCsrfToken.php
   creating: laravel-master/app/Http/Requests/
  inflating: laravel-master/app/Http/Requests/Request.php
  inflating: laravel-master/app/Http/routes.php
   creating: laravel-master/app/Jobs/
  inflating: laravel-master/app/Jobs/Job.php
   creating: laravel-master/app/Listeners/
 extracting: laravel-master/app/Listeners/.gitkeep
   creating: laravel-master/app/Policies/
 extracting: laravel-master/app/Policies/.gitkeep
   creating: laravel-master/app/Providers/
  inflating: laravel-master/app/Providers/AppServiceProvider.php
  inflating: laravel-master/app/Providers/AuthServiceProvider.php
  inflating: laravel-master/app/Providers/EventServiceProvider.php
  inflating: laravel-master/app/Providers/RouteServiceProvider.php
  inflating: laravel-master/app/User.php
  inflating: laravel-master/artisan
   creating: laravel-master/bootstrap/
  inflating: laravel-master/bootstrap/app.php
  inflating: laravel-master/bootstrap/autoload.php
   creating: laravel-master/bootstrap/cache/
 extracting: laravel-master/bootstrap/cache/.gitignore
  inflating: laravel-master/composer.json
   creating: laravel-master/config/
  inflating: laravel-master/config/app.php
  inflating: laravel-master/config/auth.php
  inflating: laravel-master/config/broadcasting.php
  inflating: laravel-master/config/cache.php
  inflating: laravel-master/config/compile.php
  inflating: laravel-master/config/database.php
  inflating: laravel-master/config/filesystems.php
  inflating: laravel-master/config/mail.php
  inflating: laravel-master/config/queue.php
  inflating: laravel-master/config/services.php
  inflating: laravel-master/config/session.php
  inflating: laravel-master/config/view.php
   creating: laravel-master/database/
 extracting: laravel-master/database/.gitignore
   creating: laravel-master/database/factories/
  inflating: laravel-master/database/factories/ModelFactory.php
   creating: laravel-master/database/migrations/
 extracting: laravel-master/database/migrations/.gitkeep
  inflating: laravel-master/database/migrations/2014_10_12_000000_create_users_t                                                                                        able.php
  inflating: laravel-master/database/migrations/2014_10_12_100000_create_passwor                                                                                        d_resets_table.php
   creating: laravel-master/database/seeds/
 extracting: laravel-master/database/seeds/.gitkeep
  inflating: laravel-master/database/seeds/DatabaseSeeder.php
  inflating: laravel-master/gulpfile.js
  inflating: laravel-master/package.json
  inflating: laravel-master/phpspec.yml
  inflating: laravel-master/phpunit.xml
   creating: laravel-master/public/
  inflating: laravel-master/public/.htaccess
 extracting: laravel-master/public/favicon.ico
  inflating: laravel-master/public/index.php
 extracting: laravel-master/public/robots.txt
  inflating: laravel-master/public/web.config
  inflating: laravel-master/readme.md
   creating: laravel-master/resources/
   creating: laravel-master/resources/assets/
   creating: laravel-master/resources/assets/sass/
  inflating: laravel-master/resources/assets/sass/app.scss
   creating: laravel-master/resources/lang/
   creating: laravel-master/resources/lang/en/
  inflating: laravel-master/resources/lang/en/auth.php
  inflating: laravel-master/resources/lang/en/pagination.php
  inflating: laravel-master/resources/lang/en/passwords.php
  inflating: laravel-master/resources/lang/en/validation.php
   creating: laravel-master/resources/views/
   creating: laravel-master/resources/views/errors/
  inflating: laravel-master/resources/views/errors/503.blade.php
   creating: laravel-master/resources/views/vendor/
 extracting: laravel-master/resources/views/vendor/.gitkeep
  inflating: laravel-master/resources/views/welcome.blade.php
  inflating: laravel-master/server.php
   creating: laravel-master/storage/
   creating: laravel-master/storage/app/
 extracting: laravel-master/storage/app/.gitignore
   creating: laravel-master/storage/framework/
  inflating: laravel-master/storage/framework/.gitignore
   creating: laravel-master/storage/framework/cache/
 extracting: laravel-master/storage/framework/cache/.gitignore
   creating: laravel-master/storage/framework/sessions/
 extracting: laravel-master/storage/framework/sessions/.gitignore
   creating: laravel-master/storage/framework/views/
 extracting: laravel-master/storage/framework/views/.gitignore
   creating: laravel-master/storage/logs/
 extracting: laravel-master/storage/logs/.gitignore
   creating: laravel-master/tests/
  inflating: laravel-master/tests/ExampleTest.php
  inflating: laravel-master/tests/TestCase.php
mv: cannot move ‘app’ to ‘../app’: Permission denied
mv: cannot move ‘artisan’ to ‘../artisan’: Permission denied
mv: cannot move ‘bootstrap’ to ‘../bootstrap’: Permission denied
mv: cannot move ‘composer.json’ to ‘../composer.json’: Permission denied
mv: cannot move ‘config’ to ‘../config’: Permission denied
mv: cannot move ‘database’ to ‘../database’: Permission denied
mv: cannot move ‘gulpfile.js’ to ‘../gulpfile.js’: Permission denied
mv: cannot move ‘package.json’ to ‘../package.json’: Permission denied
mv: cannot move ‘phpspec.yml’ to ‘../phpspec.yml’: Permission denied
mv: cannot move ‘phpunit.xml’ to ‘../phpunit.xml’: Permission denied
mv: cannot move ‘public’ to ‘../public’: Permission denied
mv: cannot move ‘readme.md’ to ‘../readme.md’: Permission denied
mv: cannot move ‘resources’ to ‘../resources’: Permission denied
mv: cannot move ‘server.php’ to ‘../server.php’: Permission denied
mv: cannot move ‘storage’ to ‘../storage’: Permission denied
mv: cannot move ‘tests’ to ‘../tests’: Permission denied
ashok@ubuntulava:/var/www/html/lvr/laravel-master$ sudo unzip master.zip
unzip:  cannot find or open master.zip, master.zip.zip or master.zip.ZIP.
ashok@ubuntulava:/var/www/html/lvr/laravel-master$ sudo mv * ../ && cd ..
ashok@ubuntulava:/var/www/html/lvr$ rm -r laravel-master && rm master.zip
rm: descend into write-protected directory ‘laravel-master’?
rm: remove write-protected regular file ‘master.zip’?
ashok@ubuntulava:/var/www/html/lvr$ ls
app        composer.json  gulpfile.js     package.json  public     server.php
artisan    config         laravel-master  phpspec.yml   readme.md  storage
bootstrap  database       master.zip      phpunit.xml   resources  tests
ashok@ubuntulava:/var/www/html/lvr$ composer install
Loading composer repositories with package information
Installing dependencies (including require-dev)





  [RuntimeException]
  /var/www/html/lvr/vendor does not exist and could not be created.



install [--prefer-source] [--prefer-dist] [--dry-run] [--dev] [--no-dev] [--no-p                                                                                        lugins] [--no-custom-installers] [--no-autoloader] [--no-scripts] [--no-progress                                                                                        ] [-v|vv|vvv|--verbose] [-o|--optimize-autoloader] [-a|--classmap-authoritative]                                                                                         [--ignore-platform-reqs] [--] [<packages>]...


ashok@ubuntulava:/var/www/html/lvr$
ashok@ubuntulava:/var/www/html/lvr$
ashok@ubuntulava:/var/www/html/lvr$ sudo composer install
Loading composer repositories with package information
Installing dependencies (including require-dev)
  - Installing vlucas/phpdotenv (v1.1.1)
    Downloading: 100%

  - Installing symfony/var-dumper (v2.7.7)
    Downloading: 100%

  - Installing symfony/translation (v2.7.7)
    Downloading: 100%

  - Installing symfony/routing (v2.7.7)
    Downloading: 100%

  - Installing symfony/process (v2.7.7)
    Downloading: 100%

  - Installing psr/log (1.0.0)
    Downloading: 100%

  - Installing symfony/debug (v2.7.7)
    Downloading: 100%

  - Installing symfony/http-foundation (v2.7.7)
    Downloading: 100%

  - Installing symfony/event-dispatcher (v2.8.0)
    Downloading: 100%

  - Installing symfony/http-kernel (v2.7.7)
    Downloading: 100%

  - Installing symfony/finder (v2.7.7)
    Downloading: 100%

  - Installing symfony/dom-crawler (v2.7.7)
    Downloading: 100%

  - Installing symfony/css-selector (v2.7.7)
    Downloading: 100%

  - Installing symfony/console (v2.7.7)
    Downloading: 100%

  - Installing swiftmailer/swiftmailer (v5.4.1)
    Downloading: 100%

  - Installing jakub-onderka/php-console-color (0.1)
    Downloading: 100%

  - Installing jakub-onderka/php-console-highlighter (v0.3.2)
    Downloading: 100%

  - Installing dnoegel/php-xdg-base-dir (0.1)
    Downloading: 100%

  - Installing nikic/php-parser (v2.0.0)
    Downloading: 100%

  - Installing psy/psysh (v0.6.1)
    Downloading: 100%

  - Installing paragonie/random_compat (1.1.4)
    Downloading: 100%

  - Installing nesbot/carbon (1.21.0)
    Downloading: 100%

  - Installing mtdowling/cron-expression (v1.0.4)
    Downloading: 100%

  - Installing monolog/monolog (1.17.2)
    Downloading: 100%

  - Installing league/flysystem (1.0.15)
    Downloading: 100%

  - Installing symfony/polyfill-util (v1.0.0)
    Downloading: 100%

  - Installing symfony/polyfill-php56 (v1.0.0)
    Downloading: 100%

  - Installing jeremeamia/superclosure (2.2.0)
    Downloading: 100%

  - Installing doctrine/inflector (v1.1.0)
    Downloading: 100%

  - Installing danielstjules/stringy (1.10.0)
    Downloading: 100%

  - Installing classpreloader/classpreloader (3.0.0)
    Downloading: 100%

  - Installing laravel/framework (v5.1.26)
    Downloading: 100%

  - Installing doctrine/instantiator (1.0.5)
    Downloading: 100%

  - Installing symfony/yaml (v3.0.0)
    Downloading: 100%

  - Installing sebastian/recursion-context (1.0.2)
    Downloading: 100%

  - Installing sebastian/exporter (1.2.1)
    Downloading: 100%

  - Installing phpspec/php-diff (v1.0.2)
    Downloading: 100%

  - Installing sebastian/diff (1.4.1)
    Downloading: 100%

  - Installing sebastian/comparator (1.2.0)
    Downloading: 100%

  - Installing phpdocumentor/reflection-docblock (2.0.4)
    Downloading: 100%

  - Installing phpspec/prophecy (v1.5.0)
    Downloading: 100%

  - Installing phpspec/phpspec (2.4.0)
    Downloading: 100%

  - Installing fzaninotto/faker (v1.5.0)
    Downloading: 100%

  - Installing hamcrest/hamcrest-php (v1.2.2)
    Downloading: 100%

  - Installing mockery/mockery (0.9.4)
    Downloading: 100%

  - Installing sebastian/version (1.0.6)
    Downloading: 100%

  - Installing sebastian/global-state (1.1.1)
    Downloading: 100%

  - Installing sebastian/environment (1.3.3)
    Downloading: 100%

  - Installing phpunit/php-text-template (1.2.1)
    Downloading: 100%

  - Installing phpunit/phpunit-mock-objects (2.3.8)
    Downloading: 100%

  - Installing phpunit/php-timer (1.0.7)
    Downloading: 100%

  - Installing phpunit/php-token-stream (1.4.8)
    Downloading: 100%

  - Installing phpunit/php-file-iterator (1.4.1)
    Downloading: 100%

  - Installing phpunit/php-code-coverage (2.2.4)
    Downloading: 100%

  - Installing phpunit/phpunit (4.8.20)
    Downloading: 100%

symfony/var-dumper suggests installing ext-symfony_debug ()
symfony/translation suggests installing symfony/config ()
symfony/routing suggests installing symfony/config (For using the all-in-one router or any loader)
symfony/routing suggests installing symfony/expression-language (For using expression matching)
symfony/routing suggests installing doctrine/annotations (For using the annotation loader)
symfony/event-dispatcher suggests installing symfony/dependency-injection ()
symfony/http-kernel suggests installing symfony/browser-kit ()
symfony/http-kernel suggests installing symfony/class-loader ()
symfony/http-kernel suggests installing symfony/config ()
symfony/http-kernel suggests installing symfony/dependency-injection ()
psy/psysh suggests installing ext-pdo-sqlite (The doc command requires SQLite to work.)
paragonie/random_compat suggests installing ext-libsodium (Provides a modern crypto API that can be used to generate random bytes.)
monolog/monolog suggests installing graylog2/gelf-php (Allow sending log messages to a GrayLog2 server)
monolog/monolog suggests installing raven/raven (Allow sending log messages to a Sentry server)
monolog/monolog suggests installing doctrine/couchdb (Allow sending log messages to a CouchDB server)
monolog/monolog suggests installing ruflin/elastica (Allow sending log messages to an Elastic Search server)
monolog/monolog suggests installing videlalvaro/php-amqplib (Allow sending log messages to an AMQP server using php-amqplib)
monolog/monolog suggests installing ext-amqp (Allow sending log messages to an AMQP server (1.0+ required))
monolog/monolog suggests installing ext-mongo (Allow sending log messages to a MongoDB server)
monolog/monolog suggests installing aws/aws-sdk-php (Allow sending log messages to AWS services like DynamoDB)
monolog/monolog suggests installing rollbar/rollbar (Allow sending log messages to Rollbar)
monolog/monolog suggests installing php-console/php-console (Allow sending log messages to Google Chrome)
league/flysystem suggests installing league/flysystem-eventable-filesystem (Allows you to use EventableFilesystem)
league/flysystem suggests installing league/flysystem-rackspace (Allows you to use Rackspace Cloud Files)
league/flysystem suggests installing league/flysystem-copy (Allows you to use Copy.com storage)
league/flysystem suggests installing league/flysystem-azure (Allows you to use Windows Azure Blob storage)
league/flysystem suggests installing league/flysystem-webdav (Allows you to use WebDAV storage)
league/flysystem suggests installing league/flysystem-aws-s3-v2 (Allows you to use S3 storage with AWS SDK v2)
league/flysystem suggests installing league/flysystem-aws-s3-v3 (Allows you to use S3 storage with AWS SDK v3)
league/flysystem suggests installing league/flysystem-dropbox (Allows you to use Dropbox storage)
league/flysystem suggests installing league/flysystem-cached-adapter (Flysystem adapter decorator for metadata caching)
league/flysystem suggests installing league/flysystem-sftp (Allows you to use SFTP server storage via phpseclib)
league/flysystem suggests installing league/flysystem-ziparchive (Allows you to use ZipArchive adapter)
laravel/framework suggests installing aws/aws-sdk-php (Required to use the SQS queue driver and SES mail driver (~3.0).)
laravel/framework suggests installing doctrine/dbal (Required to rename columns and drop SQLite columns (~2.4).)
laravel/framework suggests installing guzzlehttp/guzzle (Required to use the Mailgun and Mandrill mail drivers and the ping methods on schedules (~5.3|~6.0).)
laravel/framework suggests installing iron-io/iron_mq (Required to use the iron queue driver (~2.0).)
laravel/framework suggests installing league/flysystem-aws-s3-v3 (Required to use the Flysystem S3 driver (~1.0).)
laravel/framework suggests installing league/flysystem-rackspace (Required to use the Flysystem Rackspace driver (~1.0).)
laravel/framework suggests installing pda/pheanstalk (Required to use the beanstalk queue driver (~3.0).)
laravel/framework suggests installing predis/predis (Required to use the redis cache and queue drivers (~1.0).)
laravel/framework suggests installing pusher/pusher-php-server (Required to use the Pusher broadcast driver (~2.0).)
phpdocumentor/reflection-docblock suggests installing dflydev/markdown (~1.0)
phpdocumentor/reflection-docblock suggests installing erusev/parsedown (~1.0)
phpspec/phpspec suggests installing phpspec/nyan-formatters (~1.0 – Adds Nyan formatters)
fzaninotto/faker suggests installing ext-intl (*)
sebastian/global-state suggests installing ext-uopz (*)
phpunit/php-code-coverage suggests installing ext-xdebug (>=2.2.1)
phpunit/phpunit suggests installing phpunit/php-invoker (~1.1)
Writing lock file
Generating autoload files
> php artisan clear-compiled
> php artisan optimize
Generating optimized class loader
Compiling common classes
ashok@ubuntulava:/var/www/html/lvr$ sudo chmod -R 777 app/storage
chmod: cannot access ‘app/storage’: No such file or directory
ashok@ubuntulava:/var/www/html/lvr$ sudo service apache2 restart
 * Restarting web server apache2                                                                                                                                        AH00558: apache2: Could not reliably determine the server's fully qualified doma                                                                                        in name, using 127.0.1.1. Set the 'ServerName' directive globally to suppress th                                                                                        is message
                                                                         [ OK ]
ashok@ubuntulava:/var/www/html/lvr$
ashok@ubuntulava:/var/www/html/lvr$
ashok@ubuntulava:/var/www/html/lvr$
ashok@ubuntulava:/var/www/html/lvr$
ashok@ubuntulava:/var/www/html/lvr$ sudo chmod -R 777 app/storage
chmod: cannot access ‘app/storage’: No such file or directory
ashok@ubuntulava:/var/www/html/lvr$ sudo chmod -R 777 /app/storage
chmod: cannot access ‘/app/storage’: No such file or directory
ashok@ubuntulava:/var/www/html/lvr$ chmod -R 777 app/storage
chmod: cannot access ‘app/storage’: No such file or directory
ashok@ubuntulava:/var/www/html/lvr$ chmod -R 777 app
chmod: changing permissions of ‘app’: Operation not permitted
chmod: changing permissions of ‘app/Exceptions’: Operation not permitted
chmod: changing permissions of ‘app/Exceptions/Handler.php’: Operation not permi                                                                                        tted
chmod: changing permissions of ‘app/Jobs’: Operation not permitted
chmod: changing permissions of ‘app/Jobs/Job.php’: Operation not permitted
chmod: changing permissions of ‘app/Listeners’: Operation not permitted
chmod: changing permissions of ‘app/Listeners/.gitkeep’: Operation not permitted
chmod: changing permissions of ‘app/Http’: Operation not permitted
chmod: changing permissions of ‘app/Http/routes.php’: Operation not permitted
chmod: changing permissions of ‘app/Http/Kernel.php’: Operation not permitted
chmod: changing permissions of ‘app/Http/Requests’: Operation not permitted
chmod: changing permissions of ‘app/Http/Requests/Request.php’: Operation not pe                                                                                        rmitted
chmod: changing permissions of ‘app/Http/Controllers’: Operation not permitted
chmod: changing permissions of ‘app/Http/Controllers/Auth’: Operation not permit                                                                                        ted
chmod: changing permissions of ‘app/Http/Controllers/Auth/AuthController.php’: O                                                                                        peration not permitted
chmod: changing permissions of ‘app/Http/Controllers/Auth/PasswordController.php                                                                                        ’: Operation not permitted
chmod: changing permissions of ‘app/Http/Controllers/Controller.php’: Operation                                                                                         not permitted
chmod: changing permissions of ‘app/Http/Middleware’: Operation not permitted
chmod: changing permissions of ‘app/Http/Middleware/Authenticate.php’: Operation                                                                                         not permitted
chmod: changing permissions of ‘app/Http/Middleware/EncryptCookies.php’: Operati                                                                                        on not permitted
chmod: changing permissions of ‘app/Http/Middleware/RedirectIfAuthenticated.php’                                                                                        : Operation not permitted
chmod: changing permissions of ‘app/Http/Middleware/VerifyCsrfToken.php’: Operat                                                                                        ion not permitted
chmod: changing permissions of ‘app/Console’: Operation not permitted
chmod: changing permissions of ‘app/Console/Commands’: Operation not permitted
chmod: changing permissions of ‘app/Console/Commands/Inspire.php’: Operation not                                                                                         permitted
chmod: changing permissions of ‘app/Console/Kernel.php’: Operation not permitted
chmod: changing permissions of ‘app/Events’: Operation not permitted
chmod: changing permissions of ‘app/Events/Event.php’: Operation not permitted
chmod: changing permissions of ‘app/Policies’: Operation not permitted
chmod: changing permissions of ‘app/Policies/.gitkeep’: Operation not permitted
chmod: changing permissions of ‘app/Providers’: Operation not permitted
chmod: changing permissions of ‘app/Providers/AppServiceProvider.php’: Operation                                                                                         not permitted
chmod: changing permissions of ‘app/Providers/AuthServiceProvider.php’: Operatio                                                                                        n not permitted
chmod: changing permissions of ‘app/Providers/RouteServiceProvider.php’: Operati                                                                                        on not permitted
chmod: changing permissions of ‘app/Providers/EventServiceProvider.php’: Operati                                                                                        on not permitted
chmod: changing permissions of ‘app/User.php’: Operation not permitted
ashok@ubuntulava:/var/www/html/lvr$ sudo chmod -R 777 app
ashok@ubuntulava:/var/www/html/lvr$ cp app/
cp: missing destination file operand after ‘app/’
Try 'cp --help' for more information.
ashok@ubuntulava:/var/www/html/lvr$ cd app
ashok@ubuntulava:/var/www/html/lvr/app$ ls
Console  Exceptions  Jobs       Policies   User.php
Events   Http        Listeners  Providers
ashok@ubuntulava:/var/www/html/lvr/app$ cd ..
ashok@ubuntulava:/var/www/html/lvr$ ls
app            composer.lock  laravel-master  phpunit.xml  server.php
artisan        config         master.zip      public       storage
bootstrap      database       package.json    readme.md    tests
composer.json  gulpfile.js    phpspec.yml     resources    vendor
ashok@ubuntulava:/var/www/html/lvr$ cd ..
ashok@ubuntulava:/var/www/html$ cd ..
ashok@ubuntulava:/var/www$ sudo chmod -R 777 www
chmod: cannot access ‘www’: No such file or directory
ashok@ubuntulava:/var/www$ sudo chmod -R 777 www/
chmod: cannot access ‘www/’: No such file or directory
ashok@ubuntulava:/var/www$ sudo chmod -R 777 /www/
chmod: cannot access ‘/www/’: No such file or directory
ashok@ubuntulava:/var/www$ ls
html  lavasite
ashok@ubuntulava:/var/www$ cd .
ashok@ubuntulava:/var/www$ cd ..
ashok@ubuntulava:/var$ sudo chmod -R 777 /www/
chmod: cannot access ‘/www/’: No such file or directory
ashok@ubuntulava:/var$ sudo chmod -R 777 www/
ashok@ubuntulava:/var$ cd www/
ashok@ubuntulava:/var/www$ ll
total 16
drwxrwxrwx  4 root root 4096 Dec 12 00:48 ./
drwxr-xr-x 13 root root 4096 Dec 12 00:32 ../
drwxrwxrwx  4 root root 4096 Dec 12 00:52 html/
drwxrwxrwx  2 root root 4096 Dec 12 00:49 lavasite/
ashok@ubuntulava:/var/www$ cd lavasite/
ashok@ubuntulava:/var/www/lavasite$ ls
index.html
ashok@ubuntulava:/var/www/lavasite$ cd ..
ashok@ubuntulava:/var/www$ cd html/
ashok@ubuntulava:/var/www/html$ ls
hellox  index.html  lvr
ashok@ubuntulava:/var/www/html$ rm hellox
rm: cannot remove ‘hellox’: Is a directory
ashok@ubuntulava:/var/www/html$ rm -r hellox
ashok@ubuntulava:/var/www/html$ ls
index.html  lvr
ashok@ubuntulava:/var/www/html$ cd lvr/
ashok@ubuntulava:/var/www/html/lvr$ ls
app            composer.lock  laravel-master  phpunit.xml  server.php
artisan        config         master.zip      public       storage
bootstrap      database       package.json    readme.md    tests
composer.json  gulpfile.js    phpspec.yml     resources    vendor
ashok@ubuntulava:/var/www/html/lvr$ ls -la
total 240
drwxrwxrwx 12 root root   4096 Dec 12 01:02 .
drwxrwxrwx  3 root root   4096 Dec 12 01:07 ..
drwxrwxrwx 10 root root   4096 Dec  7 23:35 app
-rwxrwxrwx  1 root root   1646 Dec  7 23:35 artisan
drwxrwxrwx  3 root root   4096 Dec  7 23:35 bootstrap
-rwxrwxrwx  1 root root   1201 Dec  7 23:35 composer.json
-rwxrwxrwx  1 root root 111153 Dec 12 01:02 composer.lock
drwxrwxrwx  2 root root   4096 Dec  7 23:35 config
drwxrwxrwx  5 root root   4096 Dec  7 23:35 database
-rwxrwxrwx  1 root root    503 Dec  7 23:35 gulpfile.js
drwxrwxrwx  2 root root   4096 Dec 12 00:54 laravel-master
-rwxrwxrwx  1 root root  45643 Dec 12 00:53 master.zip
-rwxrwxrwx  1 root root    159 Dec  7 23:35 package.json
-rwxrwxrwx  1 root root     87 Dec  7 23:35 phpspec.yml
-rwxrwxrwx  1 root root    870 Dec  7 23:35 phpunit.xml
drwxrwxrwx  2 root root   4096 Dec  7 23:35 public
-rwxrwxrwx  1 root root   1928 Dec  7 23:35 readme.md
drwxrwxrwx  5 root root   4096 Dec  7 23:35 resources
-rwxrwxrwx  1 root root    567 Dec  7 23:35 server.php
drwxrwxrwx  5 root root   4096 Dec  7 23:35 storage
drwxrwxrwx  2 root root   4096 Dec  7 23:35 tests
drwxrwxrwx 29 root root   4096 Dec 12 01:02 vendor
ashok@ubuntulava:/var/www/html/lvr$ rm master.zip
ashok@ubuntulava:/var/www/html/lvr$ ls
app            composer.lock  laravel-master  public      storage
artisan        config         package.json    readme.md   tests
bootstrap      database       phpspec.yml     resources   vendor
composer.json  gulpfile.js    phpunit.xml     server.php
ashok@ubuntulava:/var/www/html/lvr$ cd app/
ashok@ubuntulava:/var/www/html/lvr/app$ ls
Console  Exceptions  Jobs       Policies   User.php
Events   Http        Listeners  Providers
ashok@ubuntulava:/var/www/html/lvr/app$ cd ..
ashok@ubuntulava:/var/www/html/lvr$ ls
app            composer.lock  laravel-master  public      storage
artisan        config         package.json    readme.md   tests
bootstrap      database       phpspec.yml     resources   vendor
composer.json  gulpfile.js    phpunit.xml     server.php
ashok@ubuntulava:/var/www/html/lvr$ sudo composer global require "laravel/instal                                                                                        ler=~1.1"
Changed current directory to /home/ashok/.composer
./composer.json has been created
Loading composer repositories with package information
Updating dependencies (including require-dev)
  - Installing symfony/process (v2.8.0)
    Downloading: 100%

  - Installing symfony/polyfill-mbstring (v1.0.0)
    Downloading: Connecting...
Could not fetch https://api.github.com/repos/symfony/polyfill-mbstring/zipball/0                                                                                        b6a8940385311a24e060ec1fe35680e17c74497, please create a GitHub OAuth token to g                                                                                        o over the API rate limit
Head to https://github.com/settings/tokens/new?scopes=repo&description=Composer+                                                                                        on+ubuntulava+2015-12-12+0111
to retrieve a token. It will be stored in "/home/ashok/.composer/auth.json" for                                                                                         future use by Composer.
Token (hidden):
No token given, aborting.
You can also add it manually later by using "composer config github-oauth.github                                                                                        .com <token>"
    Failed to download symfony/polyfill-mbstring from dist: Could not authentica                                                                                        te against github.com
    Now trying to download from source
  - Installing symfony/polyfill-mbstring (v1.0.0)
    Cloning 0b6a8940385311a24e060ec1fe35680e17c74497



  [RuntimeException]
  Failed to clone git@github.com:symfony/polyfill-mbstring.git, git was not f
  ound, check that it is installed and in your PATH env.
  sh: 1: git: not found



require [--dev] [--prefer-source] [--prefer-dist] [--no-progress] [--no-update]                                                                                         [--update-no-dev] [--update-with-dependencies] [--ignore-platform-reqs] [--sort-                                                                                        packages] [-o|--optimize-autoloader] [-a|--classmap-authoritative] [--] [<packag                                                                                        es>]...


ashok@ubuntulava:/var/www/html/lvr$ sudo composer global require "laravel/instal                                                                                        ler=~1.1"
Changed current directory to /home/ashok/.composer
./composer.json has been updated
Loading composer repositories with package information
Updating dependencies (including require-dev)
  - Installing symfony/polyfill-mbstring (v1.0.0)
    Downloading: Connecting...
Could not fetch https://api.github.com/repos/symfony/polyfill-mbstring/zipball/0                                                                                        b6a8940385311a24e060ec1fe35680e17c74497, please create a GitHub OAuth token to g                                                                                        o over the API rate limit
Head to https://github.com/settings/tokens/new?scopes=repo&description=Composer+                                                                                        on+ubuntulava+2015-12-12+0112
to retrieve a token. It will be stored in "/home/ashok/.composer/auth.json" for                                                                                         future use by Composer.
Token (hidden):
Invalid token provided.
You can also add it manually later by using "composer config github-oauth.github                                                                                        .com <token>"
    Failed to download symfony/polyfill-mbstring from dist: Could not authentica                                                                                        te against github.com
    Now trying to download from source
  - Installing symfony/polyfill-mbstring (v1.0.0)
    Cloning 0b6a8940385311a24e060ec1fe35680e17c74497



  [RuntimeException]
  Failed to clone git@github.com:symfony/polyfill-mbstring.git, git was not f
  ound, check that it is installed and in your PATH env.
  sh: 1: git: not found



require [--dev] [--prefer-source] [--prefer-dist] [--no-progress] [--no-update]                                                                                         [--update-no-dev] [--update-with-dependencies] [--ignore-platform-reqs] [--sort-                                                                                        packages] [-o|--optimize-autoloader] [-a|--classmap-authoritative] [--] [<packag                                                                                        es>]...


ashok@ubuntulava:/var/www/html/lvr$ cd -P
ashok@ubuntulava:~$ cd ..
ashok@ubuntulava:/home$ cd var/
-bash: cd: var/: No such file or directory
ashok@ubuntulava:/home$ cd ..
ashok@ubuntulava:/$ cd var/www/html/
ashok@ubuntulava:/var/www/html$ mkdir l
ashok@ubuntulava:/var/www/html$ chmod 777 l
ashok@ubuntulava:/var/www/html$ cd l
ashok@ubuntulava:/var/www/html/l$ laravel new blog
laravel: command not found
ashok@ubuntulava:/var/www/html/l$ sudo composer global require "laravel/installe                                                                                        r"
Changed current directory to /home/ashok/.composer
Using version ^1.2 for laravel/installer
./composer.json has been updated
Loading composer repositories with package information
Updating dependencies (including require-dev)
  - Installing symfony/polyfill-mbstring (v1.0.0)
    Downloading: 100%

  - Installing symfony/console (v2.8.0)
    Downloading: 100%

  - Installing guzzlehttp/promises (1.0.3)
    Downloading: 100%

  - Installing psr/http-message (1.0)
    Downloading: 100%

  - Installing guzzlehttp/psr7 (1.2.1)
    Downloading: 100%

  - Installing guzzlehttp/guzzle (6.1.1)
    Downloading: 100%

  - Installing laravel/installer (v1.2.2)
    Downloading: 100%

symfony/console suggests installing symfony/event-dispatcher ()
symfony/console suggests installing psr/log (For using the console logger)
Writing lock file
Generating autoload files
ashok@ubuntulava:/var/www/html/l$ ls
ashok@ubuntulava:/var/www/html/l$ la
la                 laptop-detect      lastb
landscape-sysinfo  last               lastlog
ashok@ubuntulava:/var/www/html/l$ la
la                 laptop-detect      lastb
landscape-sysinfo  last               lastlog
ashok@ubuntulava:/var/www/html/l$ cd -P
ashok@ubuntulava:~$ ~/.composer/vendor/bin
-bash: /home/ashok/.composer/vendor/bin: Is a directory
ashok@ubuntulava:~$ cd ..
ashok@ubuntulava:/home$ ~/.composer/vendor/bin
-bash: /home/ashok/.composer/vendor/bin: Is a directory
ashok@ubuntulava:/home$ composer global require "laravel/installer"
Changed current directory to /home/ashok/.composer
./composer.json is not writable.
ashok@ubuntulava:/home$ cd -P
ashok@ubuntulava:~$ sudo composer global require "laravel/installer"
Changed current directory to /home/ashok/.composer
Using version ^1.2 for laravel/installer
./composer.json has been updated
Loading composer repositories with package information
Updating dependencies (including require-dev)
Nothing to install or update
Generating autoload files
ashok@ubuntulava:~$ ~/.composer/vendor/bin
-bash: /home/ashok/.composer/vendor/bin: Is a directory
ashok@ubuntulava:~$ cd composer/vendor/bin
-bash: cd: composer/vendor/bin: No such file or directory
ashok@ubuntulava:~$ cd ..
ashok@ubuntulava:/home$ cd composer/vendor/bin
-bash: cd: composer/vendor/bin: No such file or directory
ashok@ubuntulava:/home$ ~/.composer/vendor/bin
ashok@ubuntulava:/var/www/html/lvr$ ls
app            composer.lock  laravel-master  public      storage
artisan        config         package.json    readme.md   tests
bootstrap      database       phpspec.yml     resources   vendor
composer.json  gulpfile.js    phpunit.xml     server.php
ashok@ubuntulava:/var/www/html/lvr$ cd bootstrap/
ashok@ubuntulava:/var/www/html/lvr/bootstrap$ ls
app.php  autoload.php  cache
ashok@ubuntulava:/var/www/html/lvr/bootstrap$ nano app.php
ashok@ubuntulava:/var/www/html/lvr/bootstrap$ ls
app.php  autoload.php  cache
ashok@ubuntulava:/var/www/html/lvr/bootstrap$ cd ..
ashok@ubuntulava:/var/www/html/lvr$ ls
app      bootstrap      composer.lock  database     laravel-master  phpspec.yml  public     resources   storage  vendor
artisan  composer.json  config         gulpfile.js  package.json    phpunit.xml  readme.md  server.php  tests
ashok@ubuntulava:/var/www/html/lvr$ cd config/
ashok@ubuntulava:/var/www/html/lvr/config$ ls
app.php  auth.php  broadcasting.php  cache.php  compile.php  database.php  filesystems.php  mail.php  queue.php  services.php  session.php  view.php
ashok@ubuntulava:/var/www/html/lvr/config$ cd ..
ashok@ubuntulava:/var/www/html/lvr$ ls
app      bootstrap      composer.lock  database     laravel-master  phpspec.yml  public     resources   storage  vendor
artisan  composer.json  config         gulpfile.js  package.json    phpunit.xml  readme.md  server.php  tests
ashok@ubuntulava:/var/www/html/lvr$ route
Kernel IP routing table
Destination     Gateway         Genmask         Flags Metric Ref    Use Iface
default         10.0.2.2        0.0.0.0         UG    0      0        0 eth0
10.0.2.0        *               255.255.255.0   U     0      0        0 eth0
172.13.10.0     *               255.255.255.0   U     0      0        0 eth1
192.168.122.0   *               255.255.255.0   U     0      0        0 virbr0
ashok@ubuntulava:/var/www/html/lvr$ nano a
app/     artisan
ashok@ubuntulava:/var/www/html/lvr$ nano a
app/     artisan
ashok@ubuntulava:/var/www/html/lvr$ nano a
app/     artisan
ashok@ubuntulava:/var/www/html/lvr$ nano artisan
ashok@ubuntulava:/var/www/html/lvr$ cd config/
ashok@ubuntulava:/var/www/html/lvr/config$ ls
app.php  auth.php  broadcasting.php  cache.php  compile.php  database.php  filesystems.php  mail.php  queue.php  services.php  
ashok@ubuntulava:/var/www/html/lvr/config$ cd ..
ashok@ubuntulava:/var/www/html/lvr$ ls
app      bootstrap      composer.lock  database     laravel-master  phpspec.yml  public     resources   storage  vendor
artisan  composer.json  config         gulpfile.js  package.json    phpunit.xml  readme.md  server.php  tests
ashok@ubuntulava:/var/www/html/lvr$ cd public/
ashok@ubuntulava:/var/www/html/lvr/public$ ls
favicon.ico  index.php  robots.txt  web.config
ashok@ubuntulava:/var/www/html/lvr/public$ cd ..
ashok@ubuntulava:/var/www/html/lvr$ cd tests/
ashok@ubuntulava:/var/www/html/lvr/tests$ ls

