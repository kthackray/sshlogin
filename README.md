# sshlogin
Simple Python wrapper to perform ssh connection.

## Usage
* Put ssh.cfg in your home directory
* Add your configuration. server=password. The server key supportt ildcard (wildcard match at start and end). Ex: webserver will match webserver1
* start sshlogin like the regular ssh client: sshlogin user@webserver1
