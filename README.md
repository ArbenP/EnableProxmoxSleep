# EnableProxmoxSleep
A simple guide on enabling and using sleep/suspend mode on a Proxmox server.

**Enabling Sleep Mode**

To allow your Proxmox server to enter sleep/suspend mode, open a bash shell and run the following command:

```
systemctl unmask sleep.target suspend.target hibernate.target hybrid-sleep.target
```

💡 **Note:** This command only needs to be run **once**.



**Suspending the Server**

Once enabled, you can put your Proxmox server to sleep at any time using:
```
systemctl suspend
```

# Use Cases

I have integrated this command into my _iPhone_’s _Shortcuts_ app, allowing me to suspend my server when not in use, reducing power consumption. I can then wake it remotely via **Wake-On-LAN**, eliminating the need to press the power button physically.

# **⭐ Support**

If you found this guide helpful, consider giving it a star!
