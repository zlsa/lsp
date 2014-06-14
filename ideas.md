# LSP ideas/proposals

## Graphics

* No textures
* All round items (tanks, capsules, etc.) should have the same number
  of sides, preferably a multiple of both 4 and 6 (4 for things like
  RCS, and 6 for stacking the most tanks possible); the lowest number
  that satisfies both is 12. (This is so that graphically, radially
  attached objects are always attached to a flat surface.)
* With low-poly art, it might be worth it to procedurally generate all
  of the parts on the fly (e.g. a 4m fuel tank is virtually identical
  to a 2m fuel tank).

## Physics

* Treeform proposed using a single convex hull for the entire ship.
* Problem: there is no such thing as breaking then. If you wanted to,
  you could build an entire ship that rested on a single RCS nozzle.

## Gameplay

* Thrust plates!!!!!
* Thrust plates also make it cleaner to have multiple rockets on one
  fuel tank.
* Full-sized Sol system (none of this "denser than gold" shenanigans)
* Interstages will probably be automatically generated (per top part;
  SRBs can have different interstages beneath them than than liquid
  fuel engines), like KSP.

## Edge cases

* When you have a multiple-engine thrust plate (**), the stage beneath
  it attaches to the thrust plate instead.
* When you decouple, the interstage stays attached to the previous
  stage.
* What about stage expansion and interstages; e.g. 2m engine to 4m
  first stage? Maybe should be generated procedurally.
