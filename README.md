# PHP Secure WebShell
This is just a old school php web shell, but with a password feature. You need to setup password hash before uploading and after file is uploaded need to enter password before executing commands. 

Interesting part is you don't need to enter the password for every command, instead once you type the password you can run any number of commands as you wish for your particular session. 

#### But don't forget also the r4n0mguy can do the same if he/she managed to take your session id. So make sure to terminate your session when leaving.  


## Generate password hash

`php -r "echo password_hash('yourstrongpassword', PASSWORD_DEFAULT );"`

run above command and replace the value of `$PASSWD` variable. 