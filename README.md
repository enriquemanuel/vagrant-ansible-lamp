# vagrant-ansible-lamp-test
The idea of this repository is to have the default settings to code in a LAMP stack inside Vagrant
It does the following:
* Updates apt
* Intalls Apache
* Installs a new Virtual Host for vagrant
* Disables the Default Virtual Host from Apache2
* Enables the new Virtual host
* Changes Apache User (instead of www-data) to be vagrant
* Changes Apache Group (instead of www-data) to be vagrant
* Installs PHP5 latest
* Installs Apache PHP module
* Installs PHP mcrypt module
* Installs PHP INTL module
* Modifies the php.ini file to have New_York timezone
* Installs MySQL server latest
* Installs PHP MySQL PDO
* Reloads Apache
