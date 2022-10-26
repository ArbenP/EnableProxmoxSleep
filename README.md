# EnableProxmoxSleep
A guide on how to enable, and how to put a Proxmox Server to Sleep/Suspend mode

First you enter the bash shell of the server and type in this command to enable putting sleep mode on.
Hint: you only need to do this command ***once***

    systemctl unmask sleep.target suspend.target hibernate.target hybrid-sleep.target

Now once you have entered that command, run this command to put the server to sleep mode any time.

    systemctl suspend

# Use cases
I have added this command to my *iPhone*'s *Shortcuts* app to Suspend my server, so I can easily save power when I am not using it, and then able to wake the server, through Wake-On-Lan, all without physically pressing the power button on my home server.

# If you found this useful, give it a star!

