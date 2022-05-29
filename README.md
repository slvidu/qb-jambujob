# qb-jambujob
Simple Jambu Fruit Picking Script (QB Framework)

Step 1
Add these to qb-core/shared.lua

	['jambu'] 					 	 = {['name'] = 'jambu', 			    	    ['label'] = 'jambu', 					['weight'] = 300, 		['type'] = 'item', 		['image'] = 'jambu.png', 	    	    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	  ['combinable'] = nil,   ['description'] = 'Tasty jambu'},
	
    ['jambu_mixcher'] 				         = {['name'] = 'jambu_mixcher', 			  	    ['label'] = 'Orange Juice', 			        ['weight'] = 450, 		['type'] = 'item', 		['image'] = 'jambu_mixcher.png', 	    ['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,	  ['combinable'] = nil,   ['description'] = 'Tasty Orange Juice'},

Step 2
Go to resources qb-inventory/html/images and add jambu.png & jambu_mixcher.png to images.

Step 3
Take qb-jambu out of the qb-jambujob folder and put it in the [qb] as well.

Developed By
!ViDu#0892
