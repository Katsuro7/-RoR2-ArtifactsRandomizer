# Description
Randomizes artifacts on every stage

# Config

## Randomization modes
There are 2 randomization modes: `Weight`, `Chance`. 

## Blacklist
You can add artifacts that won't be affected by randomization. If you enable artifacts that are blacklisted, they will be enabled for the whole run.

## Weight

#### Default weight
A weight that will be applied to every artifact that is not in the `ArtifactWeights` list.

#### Artifact weights
You can add weight for specific artifacts it will affect artifact enabling chance.

#### Maximum artifacts count
You can set the maximum count of artifacts that will be enabled with the `Weight` randomization mode.
If you set it to `-1` then all artifacts could be enabled at once

#### Minimum artifacts count
You can set the minimum count of artifacts that will be enabled with the `Weight` randomization mode.

## Chance

#### Default chance
A chance that will be applied to every artifact that is not in the `ArtifactChances` list.

#### Artifact chances
You can add a chance for individual artifacts.
Chance should be in a range from 0 to 1 inclusive, where 0 - artifact always disabled, 1 - artifact always enabled.

# Changelog

**2.0.0**

* Migrated to `InLobbyConfig` instead of console commands.
* Now you can use modded artifacts with this mod.
* No longer can activate artifacts that you have not unlocked.

**1.4.1**

* Marked as client side mod.
* This time actuially updated(lol)

**1.4.0**

* Added minimum count of randomized artifacts (Weight mode)
* Moved `blacklist` entry to `Main` section in config

**1.3.0**

* Added randomization modes
* Added artifact chances randomization mode

**1.2.0**

* Added maximum count of randomized artifacts
* Added weights config, so you can change artifact enabling chance

**1.1.1**

* Accidentally updated old version to `RoR` 1.0 update

**1.1.0**

* Added blacklist for artifacts.

**1.0.0**

* Mod release.