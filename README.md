# Winery-Simulator
A simulation game made in Unreal Engine 5 that provides a relaxing experience of running a winery.
This project development is currently on pause.

Play as a vintner as you grow your wine empire! Learn the basics of how wine is made, from growing and harvesting different grape varieties, to crushing and aging the juice, to bottling and packaging your orders. Use your revenue to upgrade your vineyard and wine cellar and unlock more grape varieties and wine recipes. With your new-found knowledge, take on  custom orders and create wines that match your clients' tastes, budget, and time constraints. Play precision-based mini-games for certain steps of the process to increase the wine's quality or speed up the aging process. 

This game is still in early stages of development. Feel free to download the progress to see the game so far and look at the code. Warning that it is not all cohesive yet. The purpose of this repository is to provide a demonstration of my Unreal Engine 5 knowledge for potential employers.

The three "playable" areas of this game are as follows:

1. The vineyard - Player can walk around their vineyard and pick grapes.
2. The cellar - Player can place grapes in a bowl to crush them. Once this is done, they can select the options they want for aging the wine, and then send the crushed grapes to a barrel (currently only oak barrels work) which will ferment and age the wine over a certain amount of time dependent on the aging options the player selected. When the wine is done aging, the player can fill up to 10 wooden bowls with wine from the barrel. There is a storage and bottling room where the player can set bowls of wine on shelves, along with a trashcan where they can discard any wine they don't want.
3. The packaging room - Player can pick up a box from the pile in the corner, and place it on the packaging table (which will eventually be used to pack up wine orders), a shelf, or a shipping pallet. Empty boxes can be discarded by clicking on the box pile while holding one. There is a computer where the player will eventually receive orders and buy upgrades and new recipes.

Any data that is created in one level is currently not passed to other levels when loaded. For example, the number of grapes the player has in the vineyard will be updated as they pick them, but once they go inside, that number is reset.
