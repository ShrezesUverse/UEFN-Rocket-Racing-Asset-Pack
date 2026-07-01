# UEFN Rocket Racing Asset Pack
Exposes full Fortnite’s Rocket Racing content for use in your own Unreal Editor for Fortnite (UEFN) projects. Everything that exists in Rocket Racing is included, not a partial set.

## Requirements

- Fortnite installed via the Epic Games Launcher
- Unreal Editor for Fortnite (UEFN) installed
- Fortnite and UEFN both fully closed before copying files

## Installation

Download both `.uasset` files from this repo, then:

**Find your Fortnite install directory.** Ususally at:

   ```
   C:\Program Files\Epic Games\Fortnite\
   ```

   If yours is installed elsewhere, use that path instead

**Place `DelMar.uasset`:**

   ```
   <Fortnite Install>\FortniteGame\Content\DelMar.uasset
   ```

   This `Content` folder should already exist

**Place `UEFN_Expose_DelMarCoreContent.uasset`:**

   ```
   <Fortnite Install>\FortniteGame\Plugins\GameFeatures\DelMar\DelMarCore\Content\UEFNExposedAssets\UEFN_Expose_DelMarCoreContent.uasset
   ```

   This folder chain won't exist by default maybe... if you do NOT happen to have rhose folders then just create them.
   `Plugins → GameFeatures → DelMar → DelMarCore → Content → UEFNExposedAssets`

Now, when loading into a project, goto Tortnite and you should have a DelMar folder with all content inside. You can also search for that content using the quick search bar in your content drawer.

## Final folder structure

```
Fortnite/
└── FortniteGame/
    ├── Content/
    │   └── DelMar.uasset
    └── Plugins/
        └── GameFeatures/
            └── DelMar/
                └── DelMarCore/
                    └── Content/
                        └── UEFNExposedAssets/
                            └── UEFN_Expose_DelMarCoreContent.uasset
```


## Notes

Not affiliated with or endorsed by Epic Games.

## For Epic Games

If you wish to take this down, contact me via shrezeleiprech@gmail.com

---
Enjoy!
