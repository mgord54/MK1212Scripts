Scripts for Medieval Kingdoms 1212 AD
Created by the grand DETrooper, with noobish maintenance by Tycherious.
Built using the Rome 2 Total Realism Scripting Toolkit, courtesy of the R2TR development team.

🛠️ 30/06/2025 Update – Change List
Civil War Fixes

Fixed issue where the civil war debuff for Abbasid and Epirus was not being removed when the war ended.

Faction Attribute Fixes

Seljuks: Fixed faction attribute bug — +2 experience for recruited missile cavalry now applies correctly.

Muhtasib Minister: Fixed trait bug — now properly grants +2 sanitation and +10% commerce bonuses.

Startup Bug Fix

Fixed a bug in the startup menu that incorrectly showed “missing pack files.” This feature now works as intended and will correctly notify users when packs are missing.

🏛️ Holy Roman Empire (HRE) Mechanics

HRE Voting System: Core mechanics retained, but function logic restructured. See: Transparent HRE Mechanics.

HRE Elections: Now triggers title and capital transitions upon electing a new Emperor (e.g., Frankfurt becomes imperial seat).

Dynamic Naming: “Holy Roman Empire” faction name now updates correctly based on election state.

Fixed three unique Emperor dilemmas that influence internal HRE loyalty and disloyalty mechanics.

Pretender System: The Pope can now elect pretender Catholic factions to engage with HRE mechanics again.

Election Events: Added popup message with image and text to inform the player after a new Emperor is elected.

Liberating an HRE member state as Emperor now automatically creates a military alliance and flags the state as loyal.

Puppet state logic for minor HRE factions fixed.

HRE Reform #1: Now correctly limited to 6 Prince-Electors + Emperor as voters (was improperly including 9 factions).

🔧 17/07/2025 Update – Post Fedacking Review

stance >= 0 now properly includes stance value 0 in the neutral range (0–2), ensuring no unintended exclusions.

Removed unnecessary is_human() check in puppet-state logic — AI Emperors can now assign puppet states properly.

Codebase structure and indentation improved for clarity and consistency.





