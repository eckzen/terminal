bluetooth elementary OS

Type:

	sudo nano /etc/rc.local 

which opened that file in the nano text editor. 

Then, above the exit 0 line, I added 

	rfkill block bluetooth