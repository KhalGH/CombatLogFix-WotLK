# CombatLogFix-WotLK

**CombatLogFix** is a legacy addon originally created by [Shadowed](https://www.wowinterface.com/downloads/info16001-CombatLogFix.html) during WotLK.  
This is a modified version that fixes a previously unhandled case where Rune-based spells were incorrectly excluded from the power cost filter. Details of the change can be found in [this commit](https://github.com/KhalGH/CombatLogFix-WotLK/commit/6e794a4d9c099b625352d9437974d187e2354aae).

## Features  
- Automatic Combat Log Fixing: Detects when the combat log breaks and clears it automatically.
- Spellcast Monitoring: Tracks your successful spell casts to detect broken combat log behavior, and includes a valid-spell filter to reduce false positives.
- Zone-Based Clearing: Optionally clears the combat log when changing instance types.
- In-Combat Delay: Can delay clearing the log until you're out of combat to avoid disruption.
- Fix Notification: Optionally reports when the log breaks and gets fixed.
- Adjusted Filter: The valid-spell filter now properly support Rune-based spells.

## Chat Commands  
- **`/logfix zone`** → Toggles clearing on zone type change
- **`/logfix auto`**  → Toggles clearing combat log when it breaks
- **`/logfix wait`** → Toggles not clearing until you drop combat
- **`/logfix report`** → Toggles reporting when the combat log breaks and is fixed
- **`/logfix status`** → List of set options  

## Installation  
1. [Download](https://github.com/KhalGH/CombatLogFix-WotLK/releases/download/v1.0/CombatLogFix-v1.0.zip) the addon
2. Extract the **CombatLogFix** folder into `World of Warcraft/Interface/AddOns/`.  
3. Restart the game and enable the addon.  

## Information  
- **Addon Version:** 1.0  
- **Game Version:** 3.3.5a (WotLK)  
- **Original Author:** Shadowed
- **Modified by:** Khal 
