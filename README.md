enumeration
===========

enumeration tools

 - smtp.py : Check if a single server or list of servers are listening to port 25 and can VRFY a single user or a list of users.
 
		# python smtp.py -h
		usage: smtp.py [-h] -s SERVER [-u USER]

		Check for smtp server and test email addresses

		optional arguments:
		  -h, --help            show this help message and exit
		  -s SERVER, --server SERVER
								Enter a list input of server (file)
		  -u USER, --user USER  Enter a list input of user to test email address
								(file)
		
