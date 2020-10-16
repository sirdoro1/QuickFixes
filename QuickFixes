START XAMPP
sudo /opt/lampp/lampp start

Can't connect to local MySQL server through socket '/var/run/mysqld/mysqld.sock
https://www.zyxware.com/sites/default/files/styles/user_image/public/default_images/index.png?itok=2YmREnrP

"mysql -u root -p"

or

"mysql -u root -p Password"

start mysql service

"sudo service mysql start"

or

"/etc/init.d/mysql start"

This error occurs due to multiple installations of MySQL, in the operating system.

To resolve the issue, run the following commands in your Linux terminal.

"ps -A|grep mysql"

Kill the process by using following command:

"sudo pkill mysql"

and then run command:

"ps -A|grep mysqld"

Also Kill this process by running the following command:

"sudo pkill mysqld"

Now you are fully set and can restart your MySQL server by running the following commands:

"sudo service mysql restart"

"mysql -u root -p"


