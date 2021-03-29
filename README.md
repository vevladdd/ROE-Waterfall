# Waterfall configs for Realism Overhaul mods (WIP)

Work-in-progress Waterfall configs for Realism Overhaul mods.

As it currently stands, Waterfall is a moving target that is still itself in heavy development. We always target the latest release of Waterfall, so **if something does not work, your first step should be to verify that you have updated ALL relevant mods**.

**Support requests and bug reports should be directed here, NOT to Waterfall, Realism Overhaul, or any other mods.**

## INSTALLATION INSTRUCTIONS

**Please note that the latest version (as of 2021-03-21) moved several files. Delete the `GameData/ROEngines/Waterfall` folder before updating.**

<!-- **These configurations are based on the git versions of Realism Overhaul (at least [`295cdb8`](https://github.com/KSP-RO/RealismOverhaul/commit/295cdb89d03d0fc0276e4b07f167f835be3cf206)) and ROEngines (at least [`03e06e2`](https://github.com/KSP-RO/ROEngines/commit/03e06e29ecfa751fc835ccdff10d483aee4f51a7)). Using the release (i.e., CKAN) versions of these mods will break certain plumes.** -->

1. **If you have not done so, update to the latest versions of RealismOverhaul (>= 13.0) and ROEngines (>= 1.7).**
2. **Install the latest version of [Waterfall](https://github.com/post-kerbin-mining-corporation/Waterfall).**
   * ROE-Waterfall and Waterfall are two separate things. ROE-Waterfall provides configurations for Realism Overhaul engines, Waterfall provides the effects themselves. ROE-Waterfall is to Waterfall as RealPlume-Stock is to RealPlume. *You need both.*
3. Download this package: Press the green button "Code" and click on "Download ZIP".
4. Unpack into `GameData` and *agree* to overwrite.
5. Launch the game.

If you prefer engine lights from Engine Lighting Relit instead of Waterfall, create an empty folder named `ROWaterfallNoEngineLight` under `GameData`.

The eventual goal is to merge this patchset into the relevant RO mods; this unconventional installation process is only temporary.

## Currently Configured Parts

Note: Due to technical limitations (see #1), only one plume can be provided at the moment for engines with switchable fuel configurations (ex. hypergolic and kerolox).

* Realism Overhaul
  * 1.1/1.78 kN Thruster (white hypergolic plume only)
  * 2.2/3.6 kN Thruster (white hypergolic plume only)
  * NERVA I (ReStock model only)
  * Bornholio Nuclear (ReStock models only)
    * KIWI A24
    * KIWI B48
    * NERVA NRX 50
    * NERVA XE 100
    * Pewee 100
    * Phoebus One 50
    * Phoebus Two 100
    * RD-0410 NTR
    * SNTP-PFE 100
  * NSTAR ion engine (ReStock model only)
  * RCS quads (ReStock model only)
* ROCapsules
  * Apollo
    * Command Module
    * RCS block
  * Apollo (Eyes Turned Skyward)
    * Block III+ Command Module
    * Block III Engine
    * Block V Engine
  * Orion
    * Command Module
    * European Service Module
    * RCS block
* ROEngines
  * Alcolox
    * A4
    * A-7 (alcolox plume only)
    * RD-100 (early Soviet missiles)
    * XLR-41, XLR-43 (alcolox plume only)
  * Ammonialox
    * XLR-99
  * Hydrolox
    * J-2 (Saturn V)
    * J-2X
    * HG-3
    * LR-87-LH2, sea-level and vacuum variants
    * M-1, sea-level and vacuum variants
    * RD-57
    * RD-0146
    * RD-0120 (Energiya)
    * RL-10 family (various American upper stages)
    * RS-25 (Space Shuttle)
    * RS-68 (Delta IV)
  * Hypergolic
    * Aerobee
    * Agena family (Agena upper stage)
    * Early and Mid-period AJ10 (Able and Delta upper stages)
    * AJ10-137 (Apollo spacecraft)
    * AJ10-190 (Space Shuttle)
    * AJ10 Transtar (hypergolic plume only)
    * Juno 6k
    * Juno 45k
    * KTDU-35 (Soyuz)
    * KTDU-425A (4MV and 5MV)
    * Leros 1b (white hypergolic plume only)
    * Leros 4 (white hypergolic plume only)
    * LMAE (Apollo spacecraft)
    * LMDE (Apollo spacecraft)
    * LR-87, LR-87-AJ-11 (Titan) (AZ50/NTO plume only)
    * LR-91 (Titan) (AZ50/NTO plume only)
    * R-4D (white hypergolic plume only)
    * R-40 (white hypergolic plume only)
    * R-42 (white hypergolic plume only)
    * RD-0210, RD-0211 (Proton)
    * RD-119 (Kosmos-2)
    * RD-215 (Kosmos-3, Cyclone)
    * RD-253 (Proton)
    * S400 (white hypergolic plume only)
    * S5.92 (Fregat)
    * S5.98M (Briz)
    * S-155 (E-50)
    * TD-339 (white hypergolic plume only)
    * Viking family (Ariane-1 to 4)
  * Kerolox
    * E-1
    * F-1 (Saturn V)
    * F-1B
    * H-1 family (Saturn IB)
    * LR-79 (Thor)
    * LR-89, LR-101, LR-105 (Atlas)
    * Merlin 1 family (Falcon 9)
    * NK family (N-1)
    * RD-0105 (Luna and Vostok rockets)
    * RD-0110 and its vernier (Block I)
    * RD-0124 (Angara)
    * RD-58 (Blok-D upper stage)
    * RD-107, RD-108 (R-7 family)
    * RD-120 and RD-8 (Zenit)
    * RD-170 family (Energiya, Zenit, Atlas V, Antares)
    * RZ (Blue Streak, Europa)
    * X-405 (Vanguard)
    * X-405H (Vega upper stage)
  * Kerosene + Nitric Acid
    * ORM65
    * RD-200
    * RD-211 (R-12 and Kosmos-2)
    * S2.253 (Scud)
    * Veronique (Veronique sounding rocket)
  * Methalox
    * BE-4 (Vulcan and New Glenn)
    * Raptor, sea-level and vacuum variants (Starship)
  * Monopropellant
    * MR-80 TDE
    * MR-80B (MDE)
    * MR-104
    * MR-107 (0.592 kN Dual Radial Engine)
  * Nuclear Thermal Rocket
    * Bimodal NTR
* Mandatory RCS Parts Pack
* Internal RCS
* ReStock Plus
  * RCS blocks
* Ven's New Parts
  * RCS blocks
* Real Scale Sea Dragon
  * First and second stage engines
  * TVC engine

If you find something bad here, please open an issue or a PR. Or write in the Realism Overhaul discord.

## Credit

This mod only applies templates to parts.

* Thanks to Nertea, Zorg, and the rest of the [Waterfall](https://github.com/post-kerbin-mining-corporation/Waterfall) team for providing plume templates and sound.
* The files `BDB_HTP_vernier.cfg`, `BDB_HTP_vernierVac.cfg`, `BDB_nuclear_PBR_vac.cfg`, and `GeminiWhoop.ogg` (thanks to damonvv) are from the [Bluedog Design Bureau](https://github.com/CobaltWolf/Bluedog-Design-Bureau) mod. They are shipped as part of this mod without modification.
