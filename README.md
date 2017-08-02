# Securing_SSH
/etc/ssh/sshd_config file for making SSH more secure on your Linux machine


### Always back up your sshd config file before using mine.
You'll need to set up the certificates for SSH, so the public key will be in your user's .ssh/authorized_keys file on the machine you are trying to SSH to and the private key configure on the machine you are trying to SSH from. 

Instructions for PuTTY can be found here: https://www.howtoforge.com/ssh_key_based_logins_putty
