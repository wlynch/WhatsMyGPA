WhatsMyGPA
==========

A quick, simple way for Rutgers students to check their GPA.

This script makes a simple call to the Rutgers LDAP server to find out a users GPA. Authenticate with your netid password.

There are options to automate this by supplying a password in the command line or giving a file that contains the password to use. While this does make it possible to run the utility without giving a password, I highly recommend you do NOT do this on a public machine because you would be either passing your password in or storing it in plain text. I might look into how to do this with an encrypted password in the future, but this might be something I do not have control of (since I have no idea how the server is set up).
