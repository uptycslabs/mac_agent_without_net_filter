# mac_agent_without_net_filter
The Uptycs agent for Mac (Protect and Non Protect versions) without the automatic network filter. 

In May 2025 it was reported that the Uptycs network filter on Mac would cause occasional network outages (during web meetings for example). 
The standard Uptycs Mac agent automatically deploys and enables a network filter (which caused the occasional network outage). 
If you disabled the network filter the old agent would automatically re-enable it. 
This build of the agent disables the network filter in order to avoid the network outage problem. 

Once this new package version is installed, go to 'System Settings' - 'Network' - 'Filters'
Note: 'Filters' may also be named 'VPN and Filters'
...and make sure the 'Uptycs Protect' is disabled. 



