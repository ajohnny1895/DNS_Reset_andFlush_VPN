# Resets DNS to auto, flushes DNS, and disables IPv6 Windows 7+

This is a batch script you can use to reset your IPv4 DNS to auto, disable the IPv6 option (if you are not using VPN or do not want IPv6 running on your ip address), and flushes the DNS cache.

Simply copy and paste to notepad and save as a .bat and then use task scheduler in windows to schedule this batch script at the startup or logon of your computer. You will need to set the administrative privileges or "root" control for the task scheduler so that you do not need to confirm administrator priveleges. You can also create a shortcut to the desktop of the script and set it to run with administrative privileges so that when you launch the shortcut the batch file will run with full control whenever you feel like resetting your DNS to auto or to flush your DNS cache. 
