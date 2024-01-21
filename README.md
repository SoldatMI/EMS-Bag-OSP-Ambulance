# Ranjit-EmsBag For OSP-Ambulance script for QB-Core

# Information
* A Script That Would Allow Ems To carry a Their Job Bag   

| Ranjit EMS Bag

| Preview:- https://youtube.com/watch?v=ZWsk1eNjMPE&si=EnSIkaIECMiOmarE|

| OSP-Ammbulance

| Preview:- https://youtube.com/watch?v=ZWsk1eNjMPE&si=EnSIkaIECMiOmarE|

# Required
Add this to **qb-core/shared/items.lua**
```
	["emsbag"]   	= {["name"] = "emsbag", 		["label"] = "emsbag", 	["weight"] = 150, 		["type"] = "item", 		["image"] = "emsbag.png", 			["unique"] = false,   	["useable"] = true,    ["shouldClose"] = true,    ["combinable"] = nil,   ["description"] = ""},
['tourniquet'] 	= {['name'] = 'tourniquet', 		['label'] = 'Tourniquet', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'tourniquet.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['field_dressing'] 	= {['name'] = 'field_dressing', 		['label'] = 'Field Dressing', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'field_dressing.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['elastic_bandage'] 	= {['name'] = 'elastic_bandage', 		['label'] = 'Elastic Bandage', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'elastic_bandage.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['quick_clot'] 	= {['name'] = 'quick_clot', 		['label'] = 'Quick Clot', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'quick_clot.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['packing_bandage'] 	= {['name'] = 'packing_bandage', 		['label'] = 'Packing Bandage', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'packing_bandage.png', 	['unique'] = false, ['useable'] = true, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['sewing_kit'] 	= {['name'] = 'sewing_kit', 		['label'] = 'Sewing Kit', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'sewing_kit.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['epinephrine'] 	= {['name'] = 'epinephrine', 		['label'] = 'Epinephrine', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'epinephrine.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Epinephrine, also known as adrenaline, increases the bodys pulse aswell as supress pain.'},
	['morphine'] 	= {['name'] = 'morphine', 		['label'] = 'Morphine', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'morphine.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Morphine, decreases the bodys pulse aswell as suppress pain'},
	['blood250ml'] 	= {['name'] = 'blood250ml', 		['label'] = 'Blood Pack 250ml', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'blood250ml.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['blood500ml'] 	= {['name'] = 'blood500ml', 		['label'] = 'Blood Pack 500ml', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'blood500ml.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['saline250ml'] 	= {['name'] = 'saline250ml', 		['label'] = 'Saline 250ml', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'saline250ml.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['saline500ml'] 	= {['name'] = 'saline500ml', 		['label'] = 'Saline 500ml', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'saline500ml.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	['revivekit'] 	= {['name'] = 'revivekit', 		['label'] = 'Emergency Revive Kit', 		['weight'] = 10, ['type'] = 'item', ['image'] = 'revivekit.png', 	['unique'] = false, ['useable'] = false, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = ''},
	

```
Add the image from the images/emsbag.png to your **qb-inventory/html/images/** folder

-  This script does not offer support services.
