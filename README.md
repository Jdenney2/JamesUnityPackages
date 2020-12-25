# JamesUnityPackages
 A repo made to store any unity packages that I make for future use.

Included Packages:
----------------------------------

Event System: A simple package that uses the properties of unity's scriptable objects to implement a game event system. An important note: I wrote this code while following a tutorial to learn how scriptible objects work, which can be found here: https://www.raywenderlich.com/2826197-scriptableobject-tutorial-getting-started, and as such, I claim no ownership over it. The only reason why I am including it is because the FPS Package relies on it, which is a dependency that I will remove in a future update. 

FPS Package: A set of scripts that handle a great deal of the setup for an fps game, while still leaving plenty of room to tweak and alter things to suit your needs. I've tried to avoid the scripts being dependent on one another, and to a good extent, most of the scripts should be easily removed or replaced. IMPORTANT NOTE: Graphics, sound, and AI have not been implemented in this package, as those are likely going to vary greatly from project to project. That being said, the framework should make it fairly easy to implement all three in whatever way you need.

Dependencies: Event System

TODO: Remove dependecy on the event system, improve documentation(and perhaps set up a template/tutorial level)

FUTURE PLANS/IDEAS:
---------------------------------
-A fully featured turn-based JRPG battle system
-A stratagy game package(with reasource management, etc.)
