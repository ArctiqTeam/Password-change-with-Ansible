## Create a hashed password by running the following python command
## Tested on RHEL7.4


python -c 'import crypt,getpass; print(crypt.crypt(getpass.getpass(), crypt.mksalt(crypt.METHOD_SHA512)))'
