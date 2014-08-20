evewebapp
=========

This project comprises the framework to integrate Drupal-based in game corporation websites with CCP's Eve Online using either the IGB (In Game Browser) or an external browser. It incorporates the Eve SSO functionality, providing a secure experience.

## Purpose
----------

Eve Online from CCP is a popular MMORPG with a robust system supporting 3rd party applications. Since CCP has announced a SSO functionality, it becomes useful to develop applications that are more tightly integrated with the game client, in-game corporations, individual players, as well as the general public, though this functionality will be more restrictive.

The goal here is to create a common framework around which smaller features (apps) will permit very customized websites supporting various gameplay activities, such as mining ops, fleets, corp events and calendars, as well as utilizing the Eve API and CREST functionality to gather and utilize the available information from the game in a manner that is unavailable within the standard game client.

The game client has an in-game browser that can open an external (to the game) website, authenticate using the Eve Online single-sign on, and begin using features using authorized game information in a compliant manner. One of the key ingredients is the SSO. This allows players to open their corporation's website and utilize the functionality contained there from within the game client permitting a seamless experience for the end user.

## Dependencies
---------------
[yapeal](http://github.com/Dragonrun1/yapeal)  
[Drupal CMS](http://drupal.org)  

 