About this app:
Unit Scanner is a XM8 app that will show all units in a 120m radius, it was initially ment for hiding AI (DMS) but also shows players, cars and HMG guns.

Installation:

1. copy the folder JxUnitScanner into ExAdClient\
2. edit ExAdClient\CfgFunctions.cpp and add #include "JxUnitScanner\CfgFunctions.cpp"
3. copy the folder JX into ExAdClient\XM8\Apps\
4. edit config.cpp and search for the CfgXM8 class, then add "ExAd_JX" to the extraApps[] array, then add this class

	class ExAd_JX
	{
		title = "Unit Scanner";
		controlID = 85100;					//IDC:85100 -> 85200
		logo = "ExadClient\XM8\Apps\JX\logo.paa";
		onLoad = "ExAdClient\XM8\Apps\JX\onLoad.sqf";
		onOpen = "ExAdClient\XM8\Apps\JX\onOpen.sqf";
		onClose = "ExAdClient\XM8\Apps\JX\onClose.sqf";
	};

5. ingame press 6 go to more apps and select Unit Scanner