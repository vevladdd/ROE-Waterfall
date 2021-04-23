# Waterfall configs for Realism Overhaul mods (WIP)

Work-in-progress Waterfall configs for Realism Overhaul mods.

As it currently stands, Waterfall is a moving target that is still itself in heavy development. We always target the latest release of Waterfall, so **if something does not work, your first step should be to verify that you have updated ALL relevant mods**.

**Support requests and bug reports should be directed here, NOT to Waterfall, Realism Overhaul, or any other mods.**

## INSTALLATION INSTRUCTIONS

**Please note that the latest version (as of 2021-04-16) moved several files. Delete the `GameData/ROEngines/Waterfall` and `GameData/RealismOverhaul/Waterfall_Configs` folders before updating.**

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
  * 1.1/1.78 kN Thruster
  * 2.2/3.6 kN Thruster
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
  * Apollo LEM
    * Ascent Module (LMAE + RCS)
    * LMDE
  * Apollo (Eyes Turned Skyward)
    * Block III+ Command Module
    * Block III Engine
    * Block V Engine
  * CST-100 Starliner
    * Command Module
    * Service Module
    * RS-88
  * Dynasoar
    * Aft Bay (RCS only)
    * Fuselage
    * Wings
  * Gemini (BDB models)
    * Equipment Module
    * Orbital Attitude and Maneuvering System
    * Reentry Control System
    * Retro Module
  * Mercury
    * Command Module
    * Landing and Control Module
  * Orion
    * Command Module
    * European Service Module
    * RCS block
  * Vostok
    * Support Module
* ROEngines
  * Alcolox
    * A4
    * A-7
    * RD-100 (early Soviet missiles)
    * XLR-11
    * XLR-25
    * XLR-41
    * XLR-43
  * Ammonialox
    * XLR-99
  * Hydrolox
    * BE-3 (New Shepard)
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
    * RZ.20
  * Hypergolic
    * Aerobee
    * Agena family (Agena upper stage)
    * Agena Service Propulsion System
    * Agena Equipment Rack (RCS)
    * Early and Mid-period AJ10 (Able and Delta upper stages)
    * AJ10 Advanced
    * AJ10-137 (Apollo spacecraft)
    * AJ10-190 (Space Shuttle)
    * AJ10 Transtar
    * Juno 6k
    * Juno 45k
    * KTDU-35 (Soyuz)
    * KTDU-425A (4MV and 5MV)
    * Leros 1b
    * Leros 4
    * LMAE (Apollo spacecraft)
    * LMDE (Apollo spacecraft)
    * LR-87, LR-87-AJ-11 (Titan)
    * LR-91 (Titan)
    * R-4D
    * R-40
    * R-42
    * RD-0210, RD-0211 (Proton)
    * RD-119 (Kosmos-2)
    * RD-215 (Kosmos-3, Cyclone)
    * RD-253 (Proton)
    * S5.92 (Fregat)
    * S5.98M (Briz)
    * S-155 (E-50)
    * SuperDraco, single and twin variants (Dragon spacecraft)
    * TD-339
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
    * Rutherford, sea-level and vacuum variants (Electron)
    * RZ (Blue Streak, Europa)
    * X-405 (Vanguard)
    * X-405H (Vega upper stage)
  * Kerosene + HTP
    * Gamma family
    * Stentor
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
  * Nuclear Thermal Rocket
    * Bimodal NTR
  * Generic Thrusters
    * 0.4 kN Engine (S400)
    * 0.44 kN Engine (MR-104)
    * 0.592 kN Dual Radial Engine (MR-107)
* Mandatory RCS Parts Pack
* Internal RCS
* ReStock Plus
  * RCS blocks
* Shuttle Orbiter Construction Kit
  * Forward Fuselage (RCS)
  * Aft Fuselage (RCS)
* SXT
  * LEM Descent Module
* Ven's New Parts
  * RCS blocks
* Real Scale Sea Dragon
  * First and second stage engines
  * TVC engine

If you find something bad here, please open an issue or a PR. Or write in the Realism Overhaul discord.

## `ROWaterfall` Technical Documentation

`ROWaterfall` is a set of ModuleManager patches used to easily apply Waterfall and audio effects to engines.

### Basic Usage

The minimal configuration for adding a Waterfall plume and sound effect is as follows:

```text
@PART[PartName]:BEFORE[ROWaterfall]:NEEDS[Waterfall]
{
    ROWaterfall
    {
        template = waterfall-kerolox-lower-4
        audio = pump-fed-medium-1
    }
}
```

**Note that the patch should be applied in the `:BEFORE[ROWaterfall]` pass.**

`ROWaterfall` will produce a `Module[ModuleWaterfallFX]` node and an `EFFECTS` node from this patch, removing existing effects (stock, RealPlume) as necessary. However, it is still possible to use RealPlume (or stock) effects in conjunction with `ROWaterfall` – see below.

**Only one `ROWaterfall` node will be processed for a single part.** If more complex plumes are needed, extra `ModuleWaterfallFX`es can be added manually as usual; they can coexists with `ROWaterfall`.

### Configuration Options

An `ROWaterfall` node can contain the following keys and nodes:

| <div style='min-width: 9em;'>Key or node name</div> | Required | <div style='min-width: 6em;'>Default value</div> | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| :-------------------------------------------------- | :------- | :----------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `autoConfig`                                        | No       | None                                             | Apply a predefined set of switchable plumes. This key will automatically configure `template`, `audio`, `MainPlumeTemplate {}`, and `ModuleEngineConfigs` integration. <br> The `position`, `rotation`, and `scale` values should be configured against the "default" variant, which can be viewed `Waterfall_Configs/_Processor/15_auto-config.cfg`. <br> Currently, two values are possible: `rcs` (default variant `rowaterfall-rcs-cold-gas-1`) and `genericThruster` (default variant `waterfall-hypergolic-white-upper-1`).                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `template`                                          | Yes      | N/A                                              | The desired Waterfall template name. Default Waterfall templates can be found in `Waterfall/Templates`, and RO provides supplemental templates under `Waterfall_Configs/_Templates`.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `audio`                                             | No       | None                                             | The audio template to use, a selection of which are available in `Waterfall_Configs/_Audio`. <br/> *While not strictly required, omitting this key will result in a silent engine.*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `moduleID`                                          | No       | Part's `name`                                    | Override the `moduleID` of the generated `ModuleWaterfallFX`.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `engineID`                                          | No       | `basicEngine`                                    | Set the `engineID` used for the throttle controller, if one is present.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| `transform`                                         | No       | `thrustTransform`                                | Set the value of `overrideParentTransform` on the main template. If the template is an RCS template, then the `thrusterTransformName` key of the RCS controller will also be set to this value.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| `position`                                          | No       | `0,0,0`                                          | Set the position of the main template.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `rotation`                                          | No       | `0,0,0`                                          | Set the rotation of the main template.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `scale`                                             | No       | `1,1,1`                                          | Set the scale of the main template.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `glow`                                              | No       | None                                             | Add a nozzle glow that appears at the same position and has the same size as the base of the main template. This can be used to cover up the prominent "holes" in the plumes of engines that lack emissive textures. <br/> The value can be of two forms: `_<color>`, referencing one of the `waterfall-nozzle-glow-<color>-1` templates; or `ro-<name>`, referencing one of the `rowaterfall-glow-<name>` templates. *Setting this key to any other value will result in undefined behavior*. <br/> By default, the length of the generated glow will be twice the average of the x and y `scale`s of the main template. <br/> Glows that require more complicated configuration (ex. custom positioning) should be added manually using an `ExtraTemplate` node.                                                                                                                                                                                                                                          |
| `glowStretch`                                       | No       | `1`                                              | This key applies a multiplier to the length of the generated glow. It is useful for very short nozzles, where the default length might result in unsightly clipping.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `ExtraTemplate {}`                                  | No       | None                                             | This node can be used to add extra templates (ex. for verniers) to the generated `ModuleWaterfallFX`. <br/> The `template` key is required. The `transform`, `position`, `rotation`, and `scale` keys are optional and will inherit from the parent configuration if not specified. <br/> Multiple `ExtraTemplate` nodes may be used.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `MainPlumeVariant {}`                               | No       | None                                             | Define a plume variant that can be enabled based on fuel type. This requires B9PartSwitch; thus the node should be declared with `:NEEDS[B9PartSwitch]`. If variants are present, the template declared in the parent `ROWaterfall` node is considered the "default variant". <br> The `name` and `template` keys are required. The `position`, `rotation`, and `scale` keys are optional and will inherit from the default variant. The optional `glowRecolor` key (taking the same values as `glow`) can be used to replace the glow color of the default variant. <br> Note that `ExtraTemplate`s are *not* directly switchable; this must be done [manually](#modifying-effects-generated-by-rowaterfall). <br> Multiple `MainPlumeVariant` nodes may be used, but they must have distinct `name`s. <br> Each `ModuleEngineConfigs` `CONFIG` must specify a plume variant `name` using the `b9psSubtypeName` key. If a config does not set a subtype, `ROWaterfall` will set it to the default variant. |
| `defaultMainPlumeVariantName`                       | No       | Automatically generated from `template`          | Override the name of the default plume variant, which will otherwise be a shortened version of the template name.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

Here is an example using some of the optional configuration options:

```text
@PART[ROE-LR87]:BEFORE[ROWaterfall]:NEEDS[Waterfall]
{
    ROWaterfall
    {
        template = waterfall-hypergolic-aerozine50-lower-1
        audio = pump-fed-lr87-1
        position = 0,0,0.69
        rotation = 0, 0, 0
        scale = 0.85, 0.85, 0.85
        glow = _white  // Expanding to `waterfall-nozzle-glow-white-1`.

        ExtraTemplate
        {
            template = waterfall-hypergolic-vernier-upper-2
            transform = newThrustTransform
            position = 0,0,0.011
            rotation = 0, 0, 0
            scale = 0.9, 0.9, 0.8
        }

        MainPlumeVariant:NEEDS[B9PartSwitch]
        {
            name = kerolox
            template = waterfall-kerolox-lower-4
            position = 0,0,0.69
            rotation = 0, 0, 0
            scale = 2.05, 2.05, 2.05
            glowRecolor = _yellow
        }
    }

    @MODULE[ModuleEngineConfigs]:NEEDS[B9PartSwitch]
    {
        @CONFIG[LR87-AJ-3]
        {
            %b9psSubtypeName = kerolox
        }
        @CONFIG[LR87-AJ-9-Kero]
        {
            %b9psSubtypeName = kerolox
        }
        // `ROWaterfall` will set all other configs to use the default aerozine50 plume.
    }
}
```

### Plume Templates

In addition to the templates provided by Waterfall, `ROWaterfall` also ships a number of supplemental templates.

#### `rowaterfall-cold-gas-1`

(Unrealistic-looking) template modified from `waterfall-rcs-jet-1` for cold gas generic thrusters.

IMAGE: TODO

#### `rowaterfall-glow-` family

These effects are recolors of the glows shipped with Waterfall.

Currently provided colors:

* `cold-gas`: Dim white glow.
* `hydrolox-blue`: Less brightly cyan blue glow for upper-stage hydrolox engines.
* `hydrolox-red-blue`: Transitions from red at sea-level to blue in vacuum, for sea-level hydrolox plumes.
* `hypergolic-az50`: Yellow-orangish, for use specifically with aerozine50-NTO plumes.
* `hypergolic-white`: White, without a yellow tinge, for use with generic hypergolic/monopropellant plumes.
* `methalox-blue`
* `methalox-purple`
* `ntr`
* `srm`: Bright yellow-white.

![glow gallery](https://i.imgur.com/Qxu5qon.png)

From left to right: `hydrolox-blue`, `hydrolox-red-blue` at sea level, `hydrolox-red-blue` in vacuum, `hypergolic-az50`, `hypergolic-white`, `methalox-blue`, `methalox-purple`, `ntr`.

#### `rowaterfall-hydrolox-ssme`

Another take on an authentic SSME plume.

IMAGE: TODO

#### `rowaterfall-hypergolic-superdraco`

Orange hypergolic plume with prominent shock diamonds, inspired by SpaceX SuperDraco thrusters.

![SuperDraco plume](https://i.imgur.com/qoL9MvI.jpeg)

#### `rowaterfall-hypergolic-udmh-pentaborane-lower-1`

Courtesy Spaceman Spiff.

IMAGE: TODO

#### `rowaterfall-monopropellant-hydrazine-1`

Modified from `waterfall-hydrazine-monopropellant-upper-1` to be slightly less RCS-like and oriented in the correct direction.

IMAGE: TODO

#### `rowaterfall-rcs-*` family

A pack of recolored RCS plumes for different fuel types.

IMAGE: TODO

#### `rowaterfall-srm-vac-1`

A solid kick stage template inspired by vacuum chamber testing images of the Castor 30 motor.

IMAGE: TODO

#### Templates from Bluedog Design Bureau

* `BDB_HTP_vernier`
* `BDB_HTP_vernierVac`
* `BDB_nuclear_PBR_vac`

### Audio Templates

`ROWaterfall` will generate audio effects using the default node names: `running`, `engage`, `disengage`, and `flameout`.

The following generic templates are available:

* `pressure-fed-1`
* `pump-fed-very-light-1`
* `pump-fed-light-1`
* `pump-fed-medium-1`
* `pump-fed-heavy-1`
* `pump-fed-very-heavy-1`
* `rcs-jet-1`

The series of `pump-fed` effects are increasingly crackly, based on sound effects from Rocket Sound Enhancement (shipped as part of Waterfall).

There are also the following specialized effects for use:

* `pump-fed-f1-1`, which is extra crackly and energetic.
* `pump-fed-gamma-1`
* `pump-fed-lr87-1`, with the real "whoop" startup sound.
* `pump-fed-raptor-1`, with real sound effects from SpaceX test footage.
* `pump-fed-stentor-1`

### Using RealPlume or stock effects in conjunction with Waterfall

RealPlume effects can be added in the `:AFTER[ROWaterfall]` pass if they need to coexist with `ROWaterfall`. If they are added any earlier, they will be deleted by `ROWaterfall` in `:FOR[ROWaterfall]`.

Stock (including audio) effects can be added in `:AFTER[ROWaterfall]` *as long as they have a different name than [the ones used by `ROWaterfall`](#audio-templates)*. Otherwise, see [modifying effects generated by `ROWaterfall`](#modifying-effects-generated-by-rowaterfall).

### Modifying effects generated by `ROWaterfall`

**Warning:** This is inherently fragile; do so at your own risk.

Modifications to effects (`ModuleWaterfallFX` or `EFFECTS`) generated by `ROWaterfall` can be done in `:AFTER[zROWaterfall_99_Finalize]` or a later pass. Patches *should not* be added in passes between `zROWaterfall_00` and `zROWaterfall_99`. These are used internally by `ROWaterfall` and their behavior could change at any time.

The below example modifies an `ExtraTemplate` for the `kerolox` plume variant:

```text
@PART[ROE-LR87]:AFTER[zROWaterfall_99_Finalize]:NEEDS[Waterfall,B9PartSwitch]
{
    @MODULE[ModuleB9PartSwitch]:HAS[#moduleID[rowaterfallMainPlumeSwitch]]
    {
        @SUBTYPE[kerolox]
        {
            @MODULE
            {
                @DATA
                {
                    @TEMPLATE:HAS[#templateName[waterfall-hypergolic-vernier-upper-2]]
                    {
                        @templateName = waterfall-kerolox-vernier-2
                        @position = 0,0,0
                        @rotation = 0, 0, 0
                        @scale = 1.85, 1.85, 1.5
                    }
                }
            }
        }
    }
}
```

### Adding templates to `ROWaterfall`

By convention, templates provided by `ROWaterfall` should have names beginning with `rowaterfall`.

All nozzle glows should have the same default position and size (that is, the visual size and position when `position`, `rotation`, and `scale` are all their default values) as the glows shipped with Waterfall. This is required for glow rescaling to work.

## Credit

This mod only applies templates to parts.

* Thanks to Nertea, Zorg, and the rest of the [Waterfall](https://github.com/post-kerbin-mining-corporation/Waterfall) team for providing plume templates and sound.
* The files `BDB_HTP_vernier.cfg`, `BDB_HTP_vernierVac.cfg`, `BDB_nuclear_PBR_vac.cfg`, `BDB_nuclear_PBR_sustainer_LOXaug`, and `GeminiWhoop.ogg` (thanks to damonvv) are from the [Bluedog Design Bureau](https://github.com/CobaltWolf/Bluedog-Design-Bureau) mod. They are shipped as part of this mod without modification.
* The various `rowaterfall-glow-` templates are modified from the `waterfall-nozzle-glow-*-1` templates shipped with Waterfall, originally made by Zorg.
* The `rowaterfall-hypergolic-superdraco` template is modified from the `waterfall-alcolox-lower-1` template shipped with Waterfall, originally made by Zorg.
* The `rowaterfall-hydrolox-ssme` template is modified from the `waterfall-hydrolox-lower-4` template shipped with Waterfall, originally made by Zorg.
