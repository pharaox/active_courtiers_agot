# Active Courtiers AGOT Compatibility

This is an [Active Courtiers](https://steamcommunity.com/sharedfiles/filedetails/?id=3157170996) compatibility patch for [A Game of Thrones](https://steamcommunity.com/sharedfiles/filedetails/?id=2962333032). For an overview of features and other changes, see the [Active Courtiers README](https://github.com/pharaox/active_courtiers/blob/main/README.md).

The latest version is compatible with CK3 1.12.x, Active Courtiers 0.3.x, and AGOT 0.2.2.x.

Load order:

* AGOT
* Active Courtiers
* Active Courtiers AGOT Compatibility

## Overview

Active Courtiers is already largely compatible with most mods due to its design, however it cannot properly evaluate candidates for councillor or court positions introduced by conversion mods without a compatch. This compatibility patch is making it fully compatible with AGOT. It introduces the following changes:

* Enables evaluating candidates for the new councillor and court positions introduced by AGOT. Note that some of these positions are not available to married characters, or have other special prerequisites, and so you will not be able to attract better options for them via marriage. These include:
  * *Personal Steward*, since it's only available to the Night's Watch.
  * *Kingsguard*, since once married they would no longer be eligible.
  * *Maester*, *Septon*, and *Septa*, since eligible courtiers have traits that prevent them from marrying.
* Ensures that changes to marriage interactions by AGOT are properly taken into account when evaluating marriage candidates. For example, in AGOT lowborn or bastards cannot intermarry with highborn.
* Ensures that the marriage acceptance check by AI is always using the original modifier so that changes by AGOT are properly taken into account, even if the game rule **Marriage Acceptance by AI** is set to **Quick**.

## Links

* [GitHub Repository](https://github.com/pharaox/active_courtiers_agot)
