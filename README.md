OAKVNC
===============
Oakvnc is bunch of scripts to work easier with vncserver
You can find source of script in my github: https://github.com/behradeslamifar/oakvnc

Author 
---------------
Behrad Eslamifar <b.eslamifar@cvak.ir>

Source Files
---------------
Find source files in https://github.com/behradeslamifar/oakvnc

Binary Package
---------------
Find .deb package in https://github.com/cvak/oakvnc

configuration
---------------
configuration file: /etc/oakvnc.conf

Test plan
---------------
These script test on Debian (8.0) Jessie and with Mate desktop enviroment and Lubuntu. If you test with other desktop and distro. please report me bug and successful install

Reported bugs
---------------
Parser function dont have session validation

Resolved bugs 
---------------
- Dont work in ubuntu
- Stop function only kill current config file and cant detect all vncserver session

Change log
---------------
*Version 1.2.0*
- Add list option
- Add stop-all option
- Resolved two bugs (ubuntu and kill function)
- Improved postinst script for update
