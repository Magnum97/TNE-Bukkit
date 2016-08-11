Alpha 3.0
============
Completed:
----------

* Add support for H2 in place of SQLite
  * H2 will use the SQLite configurations
  * Your SQLite database will be automatically converted for you.
* Ability to reward/charge for using potions
* Ability to reward/charge for using items
* Ability to reward/charge for crafting
* Ability to reward/charge for smelting
* Ability to reward/charge for enchanting
* Ability to reward/charge for mining
* Ability to reward/charge for brewing potions
* Ability to charge for inventory use
  * Ability to charge per use(on open)
  * Ability to create packages and charge per second of use
* Ability to disable UUID support
* Ability to allow worlds to share economy data
* Ability to allow the use of bank balances for transactions
* Ability to charge for command use
* Ability to give reward for killing a player in mobs.yml
  * You may also specify a single player's username in the same format to
  give more money if someone kills a certain player.


Needs Completed:
-----------------
* Ability to import data from iConomy
* Ability to change configurations via command
* Ability to create Auctions(?)
* Re-organize data management classes to make more sense
* Write loading/saving/backwards compatibility code for Alpha 3.0

Needs Tested:
-------------
* Account purging
* Inventory & Command Credits
* Shops
* Administrative commands
* Rewards for above completed features
* Disabling UUID support
* Shared economy data for worlds
* Bank balances for transactions
* Ability to create accounts via command


Alpha 3.1
================

* Bug fixes for Alpha 3.0
* Switch to a better solution for transactions to start eliminating the vast number of utlility classes
* Better banks to allow multiple people per bank