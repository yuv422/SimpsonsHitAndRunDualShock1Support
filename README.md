PlayStation2 The Simpsons: Hit and Run - DualShock1 patch
--------------------------------------------

These patches allow you to use a Ps1 DualShock 1 analog controller with the game.
For some reason the game only recognises DualShock2 controllers even though DualShock1 controllers work fine.

Xdelta Patches for the ISOs are included along with PS2RD cheat versions.

How it works
------------

The original game logic looks something like this

```
if (strcmp("psxDualShock2", controllerType) == 0) {
  // initialise controller
}
```

This patch simply adds a '\0' over the '2' to convert the logic into a check for the dualShock1 controller. :)

Enjoy!

