STEP Patches for STEP 2.2.8

>STEP 2.2.7 Final Version	-	Submitted on January 7, 2014
>STEP 2.2.8 Final Version	-	Submitted on January 31, 2014

>Latest revision on January 31, 2014 


All patches provided as is and were made with the Skyrim Total Enhancement Project in mind. The STEP CORE Patch was made for
users with every STEP CORE mod installed. The STEP Extended Patch was made for users with every STEP CORE + Extended mod
installed. All patches are for users with all three Skyrim DLC: Dawnguard, Hearthfire, and Dragonborn.

Credits:		Everyone who creates mods that constantly make Skyrim more beautiful and fun. (and that need patching)
				The STEP Team
				
Permission:		STEP Pack Authors:		Any supplemental patch using these patches must be distributed by Official STEP channels such as
										the STEP Nexus page, forum, or wiki. STEP Packs are built on top of STEP Core, so any pack can
										have it's own patch built from the STEP Core Patch. It is no longer possible to build a off of
										this patch without it being a master, instead use the Core patch as the new patch and rename it
										when complete. Refer to STEP Moderator EssArrBee for any questions or requests.
				
				Everyone else:			This patch merges plugins with permission from Brumbek author of SMIM, so using any texture set or
										mesh from SMIM that is included in this patch requires permission. With that being said, every other
										part is free to use. Make magic and use them how ever you like, just do not distribute the official
										versions elsewhere or to other STEP users. Direct them to the STEP Nexus page or STEP Patches GitHub
										page for the official versions. Refer to STEP Moderator EssArrBee for any questions or requests.

Requirements:	STEP Core Patch:		Skyrim with all DLC. STEP Core installed.
				STEP Extended Patch:	Skyrim with all DLC. STEP Core and Extended installed.
				STEP SoS Patch:			Skyrim. All three Sounds of Skyrim mods and Unofficial Patches installed.


Installation:	Use a mod manager to install the prefered plugin. 

				DO NOT USE MORE THAN ONE of the provided plugins together or they will conflict and overwrtie each other.
				
				>>CORE PATCH USERS:		All patches from STEP Core 2.2.8 were merged into this patch, those patches are listed below:
											-	WeaponArmorFixes_ambSkyforge_Patch.esp
											-	WeaponArmorFixes_GuardDialogueOverhaul_Patch.esp
											-	DiversePriests_ConsistentOlderPeoplePatch.esp
											-	AOS_ICS Patch.esp
											-	AOS_ADS Patch.esp
											-	AOS_RWT Patch.esp
										*If these patches were downloaded and installed either untick them or uninstall them.
										
				>>EXTENDED PATCH USERS:	All patches from STEP Extended 2.2.8 were merged into this patch, those patches are listed below:
											-	WeaponArmorFixes_ambSkyforge_Patch.esp
											-	WeaponArmorFixes_GuardDialogueOverhaul_Patch.esp
											-	DiversePriests_ConsistentOlderPeoplePatch.esp
											-	DiversePriests_BringOutYourDeadPatch.esp
											-	BetterQuestObjectives-NECPatch.esp
											-	BetterQuestObjectives-PaarDilemmaPatch.esp
											-	BetterQuestObjectives-DBForevertoMisc.esp
											-	BetterQuestObjectives-AMBSkyforgePatch.esp
											-	AOS_BlockSparkles Patch.esp
											-	AOS_EBT Patch.esp
											-	AOS_DSI Patch.esp
											-	AOS_WetandCold Patch.esp
										*If these patches were downloaded and installed either untick them or uninstall them.
		
				>>Bashed Patch users:	Wrye Bash users should make sure that the any of these patches load right before the Bashed Patch. When
										creating the bashed patch, untick the stats checkbox. Create the rest of the bashed patch normally.


STEP: CORE Patch	

	-	Changes from 2.2.8:		This patch now includes both SMIM plugins for snowy chests and for Dragonborn Falseed Tern, because of this
								permissions have changed. (see above)
								Disable or remove these two plugins:
									-	StaticMeshImprovementMod-FurnitureChestSnowFix.esp
									-	StaticMeshImprovementMod-DragonbornTernFix.esp
								Remove edits for WATER or Aquisitive Soul Gems that were in Core Patch.
								Remove dependency on Improved Closedface Helmets plugins. Use the Legendary patch provided by Weapon & Armor
								Fixes by kryptopyr.
								Forward a few locations that were not in RWT.
								Patched mods that were in conflict with Audio Overhaul for Skyrim.
									-	Realistic Water Two
									-	Imrpoved Combat Sounds
									-	Smooth Blade Draw & Sheathe
									
	-	Forwrad all Worldspace edits from DLC and unofficial pathes
		-	Forward additional Location names from Hearthfire for greater compatibiltiy with all mods
			-	0000003C:	Block -1,-1:	Sub-Block -1,-3:	00009BD6
																00009BF7
							Block -1,0:		Sub-Block -1,2:		000092B2
																000092B3
							Block 0,0:		Sub-Block 0,1:		000090A5
																000090C4
											Sub-Block 1,1:		000090A4
			-	These are to avoid houses disappearing if Hearthfire loactions do not exist. If another mod makes changes to these records the
				changes will need to be forwarded.
	-	Forward all Cell edits from DLC and unofficial patches
	-	Forward all Region edits from the DLC and unofficial patches
	-	Forward fixes from USKP that conflicts with Soul Gems Differ for 'Object Bounds'
	-	Forward fixes from WAF or USKP were needed, most from WAF except because it also has stat changes. USKP fixes were forwarded
		where it made sense like object bounds and description fixes
	-	Forward Fixes from USKP that conflict with Waterbreathing Breathless Emerge on 'Dialog Topic', added Agronian fixes from USKP
	-	Merged WAF-GDO compatibility patch to eliminate plugin
	-	Merged WAF-AMB Skyforge Weapons patch to eliminate plugin
	-	Merged Diverse Priests-Consistent Older People patch to eliminate plugin
	
STEP: Extended Patch
	
	-	Changes for 2.2.8:		All changes from STEP Core Patch since 2.2.7 (see above)
								Patched mods that were in conflict with Audio Overhaul for Skyrim.
									-	Improved Weapon Impact EFFECTS
									-	Wet & Cold
									-	Deadly Spell Impacts
									-	Enhanced Blood Textures

	-	Jan. 07 2014 Update:	Now compatible with Wearable Lanterns 3.0 and Skyrim Coin Replacer Redux instead of Skyrim Coin Replacer.
	-	Nov. 26 2013 Update:	Now compatible with Weapon and Armor Fixes 4.0, minimal changes were needed.
	-	Everything from STEP: CORE Patch carried over
	-	Forward fixes from USKP to Bring Out Your Dead on 'Cell -> Block 2 -> Sub-Block 1 -> Hall of the Dead -> Persistent' for 6 coffin containers
	-	Resolved conflict between Bring Out Your Dead and The Choice is Yours on NPC 'Perth'
	-	Forward fixes from USKP to Elemental Staves on Weapon 'Staff of Thunderbolt'
			-	Worldspace should be deleted from Elemental Staves plugin do to being completely unnecessary
	-	Forward info count from Dawnguard that conflicted with Dragons Shout with Voice on 'Dialog Topic -> PushRoDah'
	-	Forward many fixes from USKP not in More Salt Please on 'Container'
	-	Resolved conflict between SMIM Tern Fix in STEP and Ars Metallica - Dragonborn on 'Container' to forward Ars crafting feathers.
	-	Forward two fixes from USKP not in Disease Descriptions on 'Spell' for Witbane and Witbane (magicka regen halved)
	-	Forward fix from USKP not in UHFP yet for 'NPC' Gralnach for tint layers and missing item (key to mill).
	-	Merged Diverse Priests-BYOD patch to eliminate plugin
	-	Merged EBQO-Non-Essential Killable Children patch to eliminate plugin
	-	Merged EBQO-Parthunaax Dilemma patch to eliminate plugin
	-	Merged EBQO-DB Forever Misc patch to eliminate plugin
	-	Merged EBQO-AMB Skyforge Weapons patch to eliminate plugin

	
STEP SoS Patch (use 2.2.7 version)

This patch is unsupported, but is compatible with the unofficial patches and Sounds of Skyrim. This can be used with STEP Core ONLY.
The changes in this patch are included in the STEP Extended Patch.

Install this patch with STEP Core Patch only. Load after the STEP Core Patch.

Forwrad all Worldspace edits from DLC and unofficial pathes
Forward all Cell edits from DLC and unofficial patches
Forward all Region edits from the DLC and unofficial patches
