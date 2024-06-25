# Installation for Linux machine
 
- [x] Checked on Ubuntu Server 22.04 
- [x] Require Steam Cmd

Install cs2 on linux

```shell
https://linuxgsm.com/servers/cs2server/
```


Required Command 
```shell
apt install libicu-dev
```


Cs2 pack config 
```shell
	AssetBrowser
	{
		retail_filter1		"materials/decals/sprays/"
		retail_filter2		"panorama/"
		retail_filter3		"patches/"
		retail_filter4		"stickers/"
		retail_filter5		"weapons/"
		retail_filter6		"materials/models/inventory_items/"
	}

	AddonConfig	
	{
		"VpkDirectories"
		{
			"exclude"       "maps/content_examples"
			"include"		"characters"
			"include"       "maps"
			"include"       "cfg/maps"
			"include"       "materials"
			"include"       "models"
			"include"       "panorama/images/overheadmaps"
			"include"       "panorama/images/map_icons"
			"include"       "particles"
			"include"       "resource"
			"include"       "scripts/vscripts"
			"include"       "sounds"
			"include"       "soundevents"
			"include"       "lighting/postprocessing"
			"include"       "postprocess"
			"include"       "addoninfo.txt"
		} 
		"AllowAddonDownload" "1"
		"AllowAddonDownloadForDemos" "1"
		"DisableAddonValidationForDemos" "1"
	}
```