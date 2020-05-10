Modbucket presents:

Basic Staples
Version .01

A mod for Staxel.

==========

What is Basic Staples?

That depends on who you are. 

If you're a player, it's a mod that fills in the holes in the cooking system of Staxel. It will let you bake bread, make cheese, and has recipes that use every basic crop in the game. If you have other mods installed that Staples supports you may find new recipes that combine ingredients from multiple mods. At the same time: Staples won't clog up your catalog with useless ingredients. If you can lay your hands on it then there should be a recipe that can use the item. If you're a player, that's all you need to know! Go have fun.

If you're a modder, Staples gives you access to new ingredients from other mods that it supports without needing to release weird compatability patch mods. It doesn't give you access to most things that would be considered an "end product" unless that could reasonably be used to make something else (Like how carrot cakes can be made into a wedding cake in vanilla Staxel.) For how the system works see the "for modders" section at the end of the file.

==========

Mods Basic Staples interacts with:

Fully Supported*:  
	- Easter Fest

*A fully supported mod has no conflicting recipes, and has copies of ingredients and crops contained within the Basic Staples mod to make them accessible to other mods. ALL OBJECTS OR ITEMS CONTAINED IN BASIC STAPLES ARE HERE WITH THE PERMISSION OF THE ORIGINAL MODDER AND THEIR WORK IS LISTED IN THE CREDITS SECTION. 

Partly Supported**:
	Allie's Kitchen Pickles - Pickles are useable in place of Staple's Pickles.
	OilC - Patches make both oils equivalent to Staple's oil for the purposes of making cooking oil. They may or may not work if another mod decides to use oils other than "cooking oil" directly.
	StaxelBasicRecipes - Removed conflicting flour recipes. Amazingly enough, there were no other conflicts. This mod's recipes stand as alternate options. Do not recommend using this mod's cocoa recipe though: it's fast and easy to get to early but you will lose a lot of money if you use it for mass production. The animal food recipes are entirely different to give you flexibility in making emergency food.
	StaxelCookieDough - Useable in place of Staple's Cookie Dough. You'll still have the extra step of making raw cookies on a sheet of the specific type you wish.

**A partly supported mod might have some recipe conflicts with Basic Staples that have been patched. Some items in the mod might be duplicates of Basic Staples items and additional reactions may have been added to make the duplicates work in Staple recipes. The mod may have ingredients that are unavailable for use with other mods.

Non-conflicting Mods***:
	HomesteadButter
	Homestead Magic Water
	HoneyGlazedChips
	HoneyGlazedCarrots
	MoreHoney
	Pearl_Jam
	KK's Pizza
	StarJelly
	Sugar Recipe (Honey)
	Waifu Bartending

***A non-conflicting mod has no recipes that directly interfere with Basic Staples. It may have different recipes that do the same thing, (like have a different method for making cheese,) but it doesn't cause any problems. Most of these mods either add a method to craft a vanilla item, or add items that Basic Staples doesn't have. It's possible some of these may move to another category if they're updated with new items or Basic Staple's roadmap changes. 

Unsupported Mods****:

****An unsupported mod either has fundamental and irreconcilable differences with Basic Staples and/or the mod author has specifically asked Mod Bucket not to pursue compatability with their mod. There may be recipe conflicts, or there may not be. Any issues arising from an unsupported mod will not be pursued.

===========

Contributing modders to Basic Staple's Core:
----------------------

toketsupuurin:
- filled in holes in vanilla recipes.
- balance patches to vanilla prices.
- Angus cow
- rooster patch to make the rooster functional
- Grapes, Wheat, Mint
- Mill, Freezer
- Items:
	- Staples: Beef, bread dough, chicken, chopped chocolate, chopped sweet potato, cocoa butter, cocoa liquor, cocoa powder, coffee grounds, icing, Oat Flour, Oil, Pepper, Raw Sausage, Rennet, Roasted Cacao, Roasted Coffee Bean, Sprinkles, 
	- Supplies: Popsicle Stick, Muffin Pan, White Potion
	- Final Dishes: Pumbanoat bread, Artisan Dark, Pear Popsicle, Tangerine Popsicle, ChocoPear Popsicle, ChocoTangerine Popsicle, Crispy Eggplant, Ham and Cheese, Sliced Watermelon, Sweet Potato Chips, Beet Turnip Gratin, Monte Cristo, Roast Chicken, Pear Tangerine Smoothie, Watermelon Cooler

MarkGrant: Egg Patch

Contributing modders to Easter Fest content:
----------------------

toketsupuurin:
- Bunny Carrot, Black Potion, Royal Icing

Contributing modders to Midsummer Night's Feast content:
----------------------

toketsupuurin:
- Waffle Griddle, Cask
- Buttercream Frosting, Gelatin, Umami Sauce, Vinegar

==========

For Modders:

First: If you have an item you want to add to Basic Staples so that the rest of the modding community can use it: Yay! Poke a Modbucket member on either the official or Mod Bucket discords (Probably Toketsupuurin as this is mostly maintained by her,) and they'll help you work through getting it into the mod.

Second: Basic Staples has been designed to win (almost certainly) any conflicts it has with another mod. It HAS to do this to fulfill its function of working with any mod that wants to play in its sandbox. If you have a recipe that desperately needs a single sweet potato being put in the blender to result in a potato mortar... well, sorry but everyone else needs the chopped sweet potato to cook food. If you're going to play in the sandbox, please respect the fact that other modders are/might be using this stuff too. If you're having a conflict like this: talk to a Bucketeer. We'll work with you to find a solution if we can, or we'll put your mod in the conflict list if we can't come to a mutually satisfying conclusion.

Third: Basic Staples has a lot of items and recipes that don't appear to the player. All of these items have "hiddenunlesspatched" in their codes. 

You have two options for handling these items & recipies:

	Have to have a quest or something that gives the item to the player if you only want them to have a limited amount of it. Bear in mind someone else's mod might make an item visible to the player and they'll have free access to it then. 

OR

	Write a small patch file that changes at least one of these values to true:

	    "catalogueUnlockedFromStart": false, //players get instant access
	    "buyable": false, //Players can buy it from the catalog. They can also buy it from a store if you change the store's pool contain it.
	    "searchable": false, //players can find it in the creative menu.
	    "canBeEarntFromLuckyBox": false //A lucky box will drop 1 of this item ONCE only if the player has never seen it. This will unlock it in the catalog if the item has buyable set to true.

	ONLY include a value you NEED to change. Don't include any others. Set the patch's priority to "20", and the merge option to "true" unless you know what you're doing. Bear in mind, other mods need access to these items too so don't go changing other stuff that impacts an item's behavior. You can probably get away with changing the value or sell price, but don't assume those aren't changed by someone else. If you need a special version of an item for a quest that needs other attributes changed It's probably better to create a new item and link to the Basic Staples QB file.

------

Actually Adding Basic Staples items to your mod:

If you just want to use a Basic Staples item in your mod there are a few ways to go about it:

1. Make your mod dependent on Basic Staples. You can use any visible basic staples items normally and you can assume that any of the visible Staple recipes are available for your player. Add in patch files to activate any items or recipes you want your players to see. (PLEASE ONLY activate items you'll be actually using to make stuff in your mod.)

2. Make your mod independent of Basic Staples. DON'T do this for critical features of your mod. Do this only when the stuff that uses Basic Staples is like bonus content. You can safely do this with just reactions for hidden secrets for your players to find. Actually showing a recipe is trickier because if Basic Staples isn't installed the recipe will read incorrectly to the player, but if you poke a Bucketeer we can look into the possibility of adding a reciprocal patch into Basic Staples that will turn on a recipe. (This is not a preferred option, but there are circumstances where it might be acceptable to pursue, like if it's an already established mod.)

Caveats for specific ingredients:

We've tried really hard to avoid duplicate items in Basic Staples from other mods. It was inevitable that it would happen at some point though. Some mods Basic Staples will just tweak so that their recipes output a Staple product...but if the mod is small enough and it only produces 1-2 items then 

Pickles: Any recipe that uses a "pickle" should probably have a variation for the pickle from Allie's mod. Technically Allie's pickles are fermented and Staple's pickles are "quick pickles" so they would be different  products in reality. If you have a good reason not to make them equivalent, (like having recipes for both kinds of pickle,) then don't. But if you just want some random form of pickle then make duplicate reactions but only a single recipe.

Corn Oil: Avoid using this directly. Cooking oil is preferred. If you use Corn Oil, bear in mind that a player might have OilC installed.

Sunflower Oil: Avoid using this directly. Cooking oil is preferred. If you use Sunflower Oil, bear in mind that a player might have OilC installed.

Cookie Dough: Any recipe that uses cookie dough should probably have a variation for the dough from StaxelCookieDough. 

