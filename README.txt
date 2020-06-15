Modbucket presents:

Basic Staples
Version 1.0

A mod for Staxel.

==========

What is Basic Staples?

That depends on who you are. 

If you're a player, it's a mod that fills in the holes in the cooking system of Staxel. It will let you bake bread, make cheese, and has recipes that use every basic crop in the game. If you have other mods installed that Staples supports you may find new recipes that combine ingredients from multiple mods. At the same time: Staples won't clog up your catalog with useless ingredients. If you can lay your hands on it then there should be a recipe that can use the item. If you're a player, that's pretty much all you need to know! Check the section on pets just below this one if you aren't happy with the tweaks to pet gifting behavior. If you're concerned about compatability see the section after that. Go have fun!

If you're a modder, Staples gives you access to new ingredients from other mods that it supports without needing to release weird compatability patch mods. It doesn't give you access to most things that would be considered an "end product" unless that could reasonably be used to make something else (Like how carrot cakes can be made into a wedding cake in vanilla Staxel.) For how the system works see the ForModder.txt file in the same folder as this readme.

==========

On Pets:

This mod adds patches to the pet files so that they will each drop ONLY their own special kind of pet seed. Patches are included for the dragon pet, Auto Magic and Xable's pet mods. If you want the Bunny Carrot, Puppy Potato, and Cat Turnip to be dropped by all pets then delete the PetPatches folder or the subfolder for any mod you don't want affected. The vanilla pet treasure list has been patched to add the bunny carrot and puppy potato to the standard pet gift list. (That patch isn't in the PetPatches folder so you don't need to worry about it.)

==========

On Patches:

This mod adds Patches for interaction with some other Mods. You can see the lists below. If you are running a mod in the Fully Supported or Partly Supported categories you'll want to go to the "mods/Basic-Staples/VoluntaryPatches" folder. Find any mods you're running, and inside those folders if there is a "-" at the end of a file extension: rename and remove the "-". Don't do this if there's a text file in the folder indicating that the patches aren't working. (You may need to turn on the ability to see file extensions in your computer's settings.)

==========

Mods Basic Staples interacts with:

Fully Supported*:  
	- Easter Fest:
		* Patches out a few duplicate recipes and cloned some ingredients and the bunny carrot. 
		* Eggwood is not a food crop and will never be cloned.
		* Filligree Rabbits already only drop bunny carrot seeds. 
		* The Easter Fest plant is patched to drop Basic Staples Bunny Carrots. 
		* You might wind up with two stacks of bunny carrot seeds. Both produce the same crop item.
	- Dragon Pets:
		* Added a patch so that the dragons use a special dragon table. 
		* Dragons drop all three pet seeds and treasures instead of clothing.
	- Xable's Animals - Patches added to redirect the pet drop tables.
	- More Farm Animals: (This mod is DEPENDENT on Basic Staples)
		* The peanut is native to Staples and available from the beginning. (Cornucopia) The elephant makes peanuts more plentiful and useful.
		* The Elephant Splat and all derivatives are turned off in Staples. MFA turns these on. 
		* Black Ivory Coffee is available in Staples for future crafting.
		* Black Ivory Vanilla Coffee and Elephant Food are only available in MFA.
		* MFA adds 2 recipes to the Elephant Cookbook. (Which should only be turned on when you have MFA installed!)

*A fully supported mod has patches to ensure no conflicting recipes and might have copies of ingredients and crops placed within the Basic Staples mod to make them accessible to other mods. ALL OBJECTS OR ITEMS CONTAINED IN BASIC STAPLES ARE HERE WITH THE PERMISSION OF THE ORIGINAL MODDER AND THEIR WORK IS LISTED IN THE CREDITS SECTION.

---------

Partly Supported**:
	
	OilC:
		* mods\Basic-Staples\crafting\OilCPatches\ You will have to manually rename the "*.reaction-" files to "*.reaction" for full compatability!
		* Patches make both oils equivalent to Staple's oil for the purposes of making cooking oil. 
		* OilC oils may or may not work if another mod decides to use oils other than "cooking oil."
		* OilC's crusher will make Staples's oils. 
		* The Crusher is much more efficent than Staple's mill so there is incentive to use it. 
		* OilC's recipes report an incorrect results quantity. You get twice as much oil.
		* Removed OilC's recipes from sale. It's pretty obvious how it works.

	StaxelBasicRecipes:
		* Removed conflicting flour reactions and hid recipes. 
		* Do not recommend using this mod's cocoa recipe. Fast but not economical. 
		* The animal food recipes are entirely different. Flexibility!

	Auto Magic:
		* Patches added to redirect the pet drop tables.
		* Automated Recipes have not been added yet.
		
**A partly supported mod might have some recipe conflicts with Basic Staples that have been patched out. Some items in the mod might be duplicates of Basic Staples items and additional reactions may have been added to make the duplicates work in Staple recipes. Incorrect recipes May have been patched out. The mod may have ingredients that are unavailable for use with other mods. Mods that use Basic Staples might forget to include reactions for some of this mod's ingredients. 

---------

Non-conflicting Mods***:
	Allie's Kitchen Pickles - (Staples has no pickles at the moment. This will change.)
	HomesteadButter
	Homestead Magic Water - Basic Staples does NOT have a Magic Water recipe. No recipe is intended.
	HoneyGlazedChips
	HoneyGlazedCarrots
	MoreHoney
	Pearl_Jam
	KK's Pizza
	StarJelly - Basic Staples does NOT have a Star Jelly recipe. No recipe is intended.
	StaxelCookieDough
		* Not useable in place of Staple's Cookie Dough because the game hates my attempts to make that happen. This will be revisited.
	Waifu Bartending

***A non-conflicting mod has no recipes that directly interfere with Basic Staples. It may have different recipes that do the same thing, (like have a different method for making cheese,) but it doesn't cause any problems. Most of these mods either add a method to craft a vanilla item, or add items that Basic Staples doesn't have. It's possible some of these may move to another category if they're updated with new items or Basic Staple's roadmap changes. 

---------

Unsupported Mods****:
	auto baker/boiler/fryer/mixer/chopper:
		* Automated Recipes have not been added yet.
	Autokitchen by NiccyNeko:
		* Automated Recipes have not been added yet.
	Coffee in Staxel:
		* Coffee Maker would require significant editing to be compatable with Basic Staples coffee.
		* Maybe someday.
	Dairy:
		* Lots of overlap with Basic Staples. 
		* Full compatability will require coordination with Ro-Z.
		* Even partial compatability will be a large project.
	Expanded Recipes:
		* Full compatability will require coordination with 09Iraida.
		* Partial compatability will be a large project.

****An unsupported mod either has fundamental and irreconcilable differences with Basic Staples and/or the mod author has specifically asked Mod Bucket not to pursue compatability with their mod. (Or we just haven't gotten to making patches yet!) There may be recipe conflicts, or there may not be. Any issues arising from an unsupported mod will probably not be pursued.

===========

Contributing modders to Basic Staple's Core:
----------------------

toketsupuurin:
- Filled in holes in vanilla recipes so you can make bread, cheese, coffee and the like. If it's a food product in vanilla you can now craft it and there is a recipe that will USE IT if it's an ingredient.
- Balance patches to vanilla prices.
- Angus cow
- Rooster patch to make the rooster functional
- Grapes, Wheat, Mint, Puppy Potato
- Mill, Freezer
- Cornucopia, Spice Grinder, Herb Garden (And unused alternates for Cornucopia and Herb Garden.)
- Cake Stand, Cheesecake Stand, Iced Cake Standm Raspberry Pie Stand
- Cookbooks
- Dummy Items (Mark Grant's idea. He's a genius!)
- Items:
	- Crops: Grapes, Wheat, Mint, Puppy Potato, Peanut, Patch to Coconut QB.
	- Chopped Crops: Banana, Coconut, Shredded Coconut, Strawberries, Sweet Potato.
	- Staples: Beef, Boiled Sausage, Bread Dough, Chicken, Chopped Chocolate, Cocoa Butter, Cocoa Liquor, Cocoa Powder, Coconut Milk, Coconut Water, Coffee Grounds, Cookie Dough, Cooking Oil, Corn Oil, Ice Cubes, Icing, Muffin Batter, Oat Flour, Pepper, Raw Sausage, Rennet, Sprinkles, Sunflower Oil, Vanilla. Patch to Cake Batter and Pancake Batter QBs.
	- Intermediates: Blueberry Popsicle Mould, Cake Iced Batter, Chocolate Chip Cookie Unbaked, Cookie Plain Unbaked, Grape Popsicle Mould, Lime Popsicle Mould, Mint Popsicle Mould, Muffin Batter Blueberry, Muffin Batter Chocolate Chip, Muffin Batter Plain, Muffin Batter Strawberry, Orange Popsicle Mould, Pear Popsicle Mould, Pumbanoat Bread Dough, Raw Beet Turnip Gratin, Roasted Cacao, Roasted Coffee Bean, Seasoned Chicken, Strawberry Popsicle Mould, Tangerine Popsicle Mould, Uncooked Ham and Cheese. (Unused: Other Cake Batter QBs.)
	- Supplies: Popsicle Stick, Muffin Pan (Unused), White Potion, Cheesecloth.
	- Final Dishes: Pumbanoat bread, Strawberry Banana Pancakes, Artisan Blanc, Artisan Dark, Artisan Ruby, Pear Popsicle, Tangerine Popsicle, ChocoPear Popsicle, ChocoTangerine Popsicle, Circus Peanut (Plain, Banana, Lemon, Cherry, Vanilla), Espresso (Not QB), Watermelon Cooler, Crispy Eggplant, Ham and Cheese, Sliced Watermelon, Sweet Potato Chips, Beet Turnip Gratin, Monte Cristo, Roast Chicken, Jam Pear, Marmalade Tangerine, Pear Tangerine Smoothie, Patch to Jam Blackberry QB.

MarkGrant: Egg Patch

===========

Contributing modders to Easter Fest content:
----------------------

toketsupuurin:
- Bunny Carrot, Black Potion, Royal Icing, Giant Chocolate Egg, Giant Sugar Egg, Cheap Egg Mould, Chocolate Egg
- All patches.

===========

Contributing modders to Midsummer Night's Feast content:
----------------------

toketsupuurin:
- Waffle Griddle, Cask
- Buttercream Frosting, Gelatin, Umami Sauce, Vinegar


============

Contributing modders to More Farm Animals content:
----------------------

Mark Grant:
- ideas
- Elephant Splat

toketsupuurin:
- Black Ivory Coffee Beans, Roasted Black Ivory Coffee Beans, Black Ivory Coffee Grounds, Black Ivory Coffee, Elephant Cookbook, Black Ivory Vanilla Coffee.
- Peanut, Circus Peanuts (five colors).

===========

Versions

1.0 
	- Cookbooks no longer make bug spawners.
	- Recipe and Cookbook Buy/Sell prices been adjusted.
	- Tags are corrected.
	- Elephant ingredients and products integrated into mod. Elephant Cookbook moved to MFA.
	- Cornucopia, Herb Garden, Spice Grinder added.
	- Cake stand and missing display food added.
	- Vanilla Added.
	- Changed how unused items work. More foolproof and less horrible codes.
	- Cheesecloth, Coconut Milk, Coconut Water added.
	- Cookbook Candy2 added.
	- Some Dummy items added. More will be added as needed/We feel like it.
	- Easterfest ingredients integrated and patches made. Old Easter chocolate eggs can be melted into chocolate bars or Giant Chocolate Eggs. Excess you can't melt down can be sold. Royal Icing, Cheap Egg Moulds, Giant Chocolate Eggs, Giant Sugar Eggs, and Black Potions should be sold. 
	- Mermaid Hoe added.
	- Reaping added for all new crops. Old Easter bunny carrots can be reaped for seeds. Old bunny carrots seeds can be planted for Staples Bunny Carrots.

0.01 
	- Released for beta test. 
	- Recipe and Cookbook Buy/Sell prices have not been adjusted.
	- Tags are all wrong.
	- Pet integration.
	- Angus and Rooster Added
	- Puppy Potato, Grapes, Wheat, Mint added
	- Easter Fest Bunny carrot integration.
	- Deep freezer and Mill added. (Cask and Waffle Iron are non-functional.)
