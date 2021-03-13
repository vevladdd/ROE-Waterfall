# Waterfall configs for Realism Overhaul mods (WIP)

Work-in-progress Waterfall configs for Realism Overhaul mods.

**Support requests and bug reports should be directed here, NOT to Waterfall, Realism Overhaul, or any other mods.**

## INSTALLATION INSTRUCTIONS

**Please note that the latest version moved several files. Delete the `GameData/ROEngines/Waterfall` folder when updating.**

**These configurations are based on the git versions of Realism Overhaul (at least [`295cdb8`](https://github.com/KSP-RO/RealismOverhaul/commit/295cdb89d03d0fc0276e4b07f167f835be3cf206)) and ROEngines (at least [`03e06e2`](https://github.com/KSP-RO/ROEngines/commit/03e06e29ecfa751fc835ccdff10d483aee4f51a7)). Using the release (i.e., CKAN) versions of these mods will break certain plumes.**

1. Install the latest version of [Waterfall](https://github.com/post-kerbin-mining-corporation/Waterfall).
2. Download this package: Press the green button "Code" and click on "Download ZIP".
3. Unpack into `GameData` and *agree* to overwrite.
4. Launch the game.

If you prefer engine lights from Engine Lighting Relit instead of Waterfall, create an empty folder named `ROWaterfallNoEngineLight` under `GameData`.

The eventual goal is to merge this patchset into the relevant RO mods; this unconventional installation process is only temporary.

## Currently Configured Parts

Note: Due to technical limitations (see #1), only one plume can be provided at the moment for engines with switchable fuel configurations (ex. hypergolic and kerolox).

* ROEngines
  * Alcolox
    * A-6 (alcolox plume only)
    * RD-100 (early Soviet missiles)
    * XLR-41, XLR-43 (alcolox plume only)
  * Hydrolox
    * J-2 (Saturn V)
    * J-2X
    * HG-3
    * LR-87-LH2, sea-level and vacuum variants
    * M-1, sea-level and vacuum variants
    * RL-10 family (various American upper stages)
    * RS-25 (Space Shuttle)
    * RS-68 (Delta IV)
  * Hypergolic
    * Agena family (Agena upper stage)
    * Early and Mid-period AJ10 (Able and Delta upper stages)
    * AJ10-137 (Apollo spacecraft)
    * LMAE (Apollo spacecraft)
    * LMDE (Apollo spacecraft)
    * LR-87, LR-87-AJ-11 (Titan) (AZ50/NTO plume only)
    * LR-91 (Titan) (AZ50/NTO plume only)
    * RD-0210, RD-0211 (Proton)
    * RD-253 (Proton)
  * Kerolox
    * E-1
    * F-1 (Saturn V)
    * F-1B
    * H-1 family (Saturn IB)
    * LR-79 (Thor)
    * LR-89, LR-101, LR-105 (Atlas)
    * NK family (N-1)
    * RD-0105 (Luna and Vostok rockets)
    * RD-58 (Blok-D upper stage)
    * RD-107, RD-108 (R-7 family)
    * RD-170 family (Energiya, Zenit, Atlas V, Antares)
    * X-405 (Vanguard)
    * X-405H (Vega upper stage)
  * Methalox
    * BE-4 (Vulcan and New Glenn)
    * Raptor, sea-level and vacuum variants (Starship)
* Realism Overhaul
  * RCS blocks from ReStock
  * RCS blocks from ReStock Plus
  * RCS blocks from Ven's New Parts

If you find something bad here, please open an issue or a PR. Or write in the Realism Overhaul discord.

## Credit

This mod only applies templates to parts.

* Thanks to Nertea, Zorg, and the rest of the [Waterfall](https://github.com/post-kerbin-mining-corporation/Waterfall) team for providing plume templates and sound.
* Thanks to damonvv for the GeminiWhoop sound.
* The files `BDB_HTP_vernier.cfg`, `BDB_HTP_vernierVac.cfg` and `GeminiWhoop.ogg` are from the [Bluedog Design Bureau](https://github.com/CobaltWolf/Bluedog-Design-Bureau) mod. They are shipped as part of this mod without modification.
