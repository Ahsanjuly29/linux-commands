# Change Hostname on Ubuntu(NO-REBOOT required)
$ hostnamectl set-hostname new-hostname
$ hostnamectl

# Change the Pretty Hostname
$ hostnamectl set-hostname "new-hostname" --pretty
$ 

# Open Xampp in Linux
$ sudo /opt/lampp/./manager-linux-x64.run

# How to check what port mysql is running on? 
$ netstat -tlnp
 
# reset Root password using bash
1. Execute bash as root using ur login password
$ sudo bash

2. Change root password using:
$ passwd root

#reset mysql Password on Linux
`$  sudo mysql -u root
    use mysql;
    SELECT user, plugin FROM user;
    UPDATE user SET plugin = "mysql_native_password" WHERE user = "root" ;
    exit
    service mysql restart
    
# Access to Mysql in Terminal
1. Using Password : mysql -u root -p 
2. not Password : mysql -u root


