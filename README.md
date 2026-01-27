This is a work-in-progress script to use in conjunction with the online RPG game, Torn.

https://www.torn.com/index.php

The git hub page for this script is: https://lordxerra.github.io/War-Dashboard/Torn-War-Dashboard.html

Note: I have deliberately avoided trying to integrate with the game interface at all and all information supplied in the git hub page is retrieved via the API.

Torn allows you to look at information via the API but not interfere with the game in any way such as simulating a button press. Every action must be taken within the game itself so this page gives you links to jump between player profiles via the game itself to attack players.

The script sets up a web page display of any faction you choose just by putting in a public API key from your settings and entering a faction ID - which you can find by opening a faction page within Torn itself and checking the ID number at the end of the url. It's usually 5 numbers in length. The script will only save your public API key, torn stats key (if in use) and the faction you are looking at using local browser so there is no data stored from what's displayed outside of your own web browser files at all.

I use the panel to keep an eye on the enemy faction when in a ranked war as it's easier and much faster than using the torn stats enemy faction display for keeping track of who's online/offline/attackable/hospitalised/travelling and so on. The panel also displays what I consider pertinent information about each member of the faction such as level, xanax used, highest damage stat, life pool and all sorts of other stuff. This information is scraped from the public information anyone can get from a player profile in Torn, hence only using a perfectly safe public key for access.

When you see a player you want to interact with - translation, shoot the hell out of them, then you can just click the skull next to their name and the page will take you to their attack page, whereas clicking the name takes you to the player profile in Torn. You can also do the usual sort and filtering stuff to make it easier to keep track of only the players you are interested in.

The page now also supports looking up previous factions you have warred against in the faction spy tab, and will use torn stats data, if you have recorded it previously in your factions profile there. Keeping torn stats up to date with spy information is very helpful when using this war portal.
