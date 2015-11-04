# vagrant-ansible-lamp-test
The idea of this repository is to have the default settings to code in a LAMP stack inside Vagrant.

If something is needed, or needs to be by default, I will continue to add it. This should be the basic provision for any basic LAMP stack or development a Symfony app.

Followed the tutorial from https://adamcod.es/2014/09/23/vagrant-ansible-quickstart-tutorial.html as well as added a custom ideas from http://stdout.in/en/post/getting_started_with_vagrant_automated_dev_servers_deploy_and_provisioning and finally used some ideas of the user and groups from here http://nater1067.github.io/blog/2014/08/25/spinning-up-symfony-2-development-environments-with-vagrant/

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
