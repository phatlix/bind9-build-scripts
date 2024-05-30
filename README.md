# BIND9 Build Scripts

### BIND9 Install

Tested and works on:  
* Rocky Linux 8.9

Here are a couple scripts.

I wanted a way to standup a primary DNS server or a quick way to rebuild that server.  But I also wanted a way to standup or rebuild a secondary server without a need to edit my single script each time.  Plus, I find that when I have to edit scripting like that, I am seriously prone to error and will screw something up.  So two build scripts.  

At the top of each will be some variables that need defined, that pertain to your setup.  I am leaving information filled in for both scripts, in hopes that it gives some insight into what belongs there.  I have tested these scripts (with the variables that are in them) and they worked ~~flawless~~ for me.  
_(cant say flawless, when my original import was a older version)_

v1
