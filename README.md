About this app:
Unit Scanner is a XM8 app that will show all units in a 120m radius, it was initially ment for hiding AI (DMS) but also shows players, cars and HMG guns.

Installation: 
* you need ExAd Core and ExAd XM8 installed for this to work
you can get them here http://www.exilemod.com/topic/13865-exad-package-of-virtual-garagexm8statsbarhalo-parachuteadmin-eventshackinggrindingvehicle-upgrade/

1. copy the folder JxUnitScanner into ExAdClient\
2. edit ExAdClient\CfgFunctions.cpp and add #include "JxUnitScanner\CfgFunctions.cpp"
3. copy the folder JX into ExAdClient\XM8\Apps\
4. edit config.cpp and search for the CfgXM8 class, then add "ExAd_JX" to the extraApps[] array, then add the contents of cfgXM8_codeSnippet.txt
5. ingame open the XM8, then go to More and select Unit Scanner


Thanks: 
Janski - for making a tutorial on how to create Apps and use the Editor to debug them.
