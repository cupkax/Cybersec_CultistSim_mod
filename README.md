# Branch Info
This is the release branch of the mod. Ideally, there should be no errors while running this branch.
# Cybersec_CultistSim_mod
This is a Cultist Simulator mod to explore moral gameplay in cybersecurity space.

# Resources
- [Modding Guide for the game](https://docs.google.com/document/d/1BZiUrSiT8kKvWIEvx5DObThL4HMGVI1CluJR20CWBU0/edit#heading=h.nzan7yxetc3l)
- [All game assets and descriptions](https://uadaf.theevilroot.xyz/frangiclave/)

# Checklist
- [x] Core loop - Randomly generate low/hisk patients at intervals.
- [x] Core loop - Use medical resources to treat patients and generate hospital funds.
- [x] Core loop - Generate medical resources using hospital funds.
- [x] Core loop - Convert low-risk patients to high-risk | high-risk patients to corpses after x seconds
- [x] Scenario1 - Create a drain on medical resources after x seconds
- [x] Scenario1 - Use cybersecurity resources to remove the drain
- [x] Scenario1 - Use investigate card on the drain tile
- [ ] Scenario1 - Generate scenario after using investigate tile
- [x] Scenario1 - Ignore drain tile -> causes more drain tiles to spawn


# Installation
## Prerequisites
The game relies on three existing mods from the steam workshop:
1.Download the following mods from steam workshop links:

  a. [GHIRBI](https://steamcommunity.com/sharedfiles/filedetails/?id=2901287611)
  
  b. [AchieveIntegrations](https://steamcommunity.com/sharedfiles/filedetails/?id=2363532185)
  
  c. [The Roost Machine](https://steamcommunity.com/workshop/filedetails/?id=2625527332)
  
## Cloning the repo
1. (Windows) Clone the repository in %userprofile%\appdata\locallow\Weather Factory\Cultist Simulator\mods in Cybersec directory
2. (MacOS) Clone the repository in $HOME/Library/Application Support/biz.weatherfactory.cultistsimulator/mods in Cybersec directory.
3. Create the mods folder, if it doesn't exist
   ```git clone https://github.com/cupkax/Cybersec_CultistSim_mod Cybersec```
4. Make sure directory structure is as follows:
```
WINDOWS
%userprofile%
└── appdata
    └── locallow
        └── Weather Factory
            └── Cultist Simulator
                └── mods
                    └── Cybersec
```
```
MACOS
$HOME
└── Library
    └── Application Support
        └── biz.weatherfactory.cultistsimulator
            └── mods
                └── Cybersec
```

4. Run the game and navigate to **Secret Histories** on top right. A new legacy, Hospital Systems Administrator, should appear.
5. Make sure the mod order is as follows:
   
   i. GHIRBI (loads first)
   
   ii. achieveIntegrations
   
   iii. The Roost Machine
   
   iv. Hospital Cybersecurity Simulator
