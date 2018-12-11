THE PROPERTIES FILE YOU CREATE HAS TO BE SAVED AS .PROPERTIES TO WORK

DEFAULT - THESE HAVE TO BE IN FOR IT TO WORK.

type=<item | enchantment | armor>
items=<item id, F3+H shows the id number, e.g. items=0276>
texture=<name of texture file, e.g. texture=Master_Sword.png>

If you were to just do the above this would change the diamond sword texture

OPTIONAL - YOU CAN PICK AND CHOOSE

damage=<number of uses, so the texture would change when it's been used this number of times - good for showing damaged weapons or armor>
stackSize=<number in a stack before it changes texture>
enchantmentIDs=<enchantment number, can get this from the Minecraft Wiki>
enchantmentLevels=<enchanting level e.g. 3 = ENCHANTMENT 3>
nbt.display.Name=<4 options to choose from; pattern:, ipattern:, regex:(A|B), iregex:(A|B). Pattern is it has to exactly this to work and is case sensitive. iPattern is the same but isn't case sensitive. Regex is it can contain either or, e.g. regex:(Master Sword|Sword of Evil's Bane) and iregex is the same but doesn't have to be case sensitive.