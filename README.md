# 👻 Codejam-eldritch 

*Helper application for the board game «Ancient Horror».*
*Link to the page* –– **[«Ancient Horror»](https://kotangenss.github.io/codejam-eldritch/)**

---
##### Description
To assemble a deck of myths, three different types of cards are used: blue, brown and green (the type is determined by the color of the strip in the card header) In addition, there are different card complexity:

> * complex cards have tentacles around the title;
> * ordinary cards do not know any signs;
> * light cards have an image of snowflakes around.

At the first stage, the player will need to choose an Ancient who will indicate the deck layout and how many cards of what color are needed at each stage of the game.

The composition of cards required for the game is calculated by the sum of cards of different colors for all 3 stages.

The next step is to determine the difficulty of the game.
From the general set of cards, you will need to select cards according to the selected difficulty:

> * very easy difficulty level: all cards with snowflakes are taken from the set, if there are not enough cards, ordinary cards are taken;
> * easy difficulty level: cards with tentacles are removed from the set;
> * medium difficulty level: the set remains intact;
> * high level of difficulty: cards with snowflakes are removed from the set;
> * very high level of difficulty: all cards with tentacles are taken from the set, if there are not enough cards, ordinary cards get there.
