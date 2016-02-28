# OpsComm-Server-Core
##The basic Opscomm server. 

As devops technology grows teams are often presented with a number of tools that we use everyday. While these tools do a great job of maintaing and tracking thier section of the lab, it also means that we have to know and acess a number of different systems to just get information day to day.

OpsComm intends to be a middleware application that leverages the power of each of these tools allowing them to do thier jobs while pulling together the simple tasks into a single interface. 

For example, Tracking the location of a host's network port might invlove a dns lookup, a search in your DCIM app, and looking through a switch config. Opscomm will pull the data from all of these datastores with one simple lookup:

**opscomm search hostname**

Loookups and searches in 3 applications combined down to one cli command.

In order to do this, the server uses "datastores" to individually lookup and format the information from all of these different sources before it's handed off to the client application. 

More information on datastores can be found at TODO. 

