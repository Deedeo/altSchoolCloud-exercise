# AltSchoolCloud Exercise

## EXERCISE 5b

### Install PHP 7.4 on your local linux machine using the ppa:ondrej/php package repo.

### Follow this steps

 * Update the apt-get to ensure that we are working with the latest version by running this command _$_ **sudo apt-get update**
 
 * Next, install software-properties-common, which adds management for additional software sources by running this command. The **-y** is to automate all installation instead of getting a prompt for each update.
 
     _$_ **sudo apt -y install software-properties-common**
 
 * Next, install the repository **ppa:ondrej/php**, which gave all the versions of PHP:
 
     _$_ **sudo add-apt-repository ppa:ondrej/php**
 
 * You should update **apt-get** again so your package manager can see the newly listed packages.
 
    _$_ **sudo apt-get update**
    
 * Then, ready to install PHP 7.4 using the following command.
 
    _$_ **sudo apt -y install php7.4**
    
 * Check the version installed:
 
    _$_ **php -v**
    
 * The Output:
 
 ![php7.4]()
 
 
 
 
 
 