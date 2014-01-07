STEP Patches for STEP 2.2.7
>Submitted on November 26, 2013

>Latest revision January 7, 2014


All patches provided as is and were made with the Skyrim Total Enhancement Project in mind. The STEP CORE Patch was made for
users with every STEP CORE mod installed. The STEP Extended Patch was made for users with every STEP CORE + Extended mod
installed. All patches are for users with all three Skyrim DLC: Dawngurad, Hearthfire, and Draognborn.

Credits:		Everyone who creates mods that make Skyrim constantly more beautiful and fun. (and that need patching)
				The STEP Team
				
Permission:		STEP Pack Authors:		STEP Packs are built on top of STEP Packs, so any pack can have it's own patch built off of
										the STEP Core Patch. Refer to STEP Moderator EssArrBee for any questions.
				
				Everyone else:			Make magic and use them how ever you like, just do not distribute the official versions elsewhere
										or to other STEP users. Direct them to the STEP Nexus page or STEP Patches GitHub page for the
										official versions.

Requirements:	STEP Core Patch:		Skyrim with all DLC. STEP Core installed.
				STEP Extended Patch:	Skyrim with all DLC. STEP Core and Extended installed.
				STEP SoS Patch:			Skyrim. All three Sounds of Skyrim mods installed.


Installation:	Use a mod manager to install the prefered plugin. 

				DO NOT USE MORE THAN ONE of the provided plugins together or they will conflict and overwrtie each other.
				
				>>CORE PATCH USERS:		Disable Weapon & Armor Fixes/Guard Dialog Overhaul Patch
										Disable Weapon & Armor Fixes/aMidianBorn Skyforge Weapons Patch
										Disable Diverse Priests/Consistent Older People patch
										These three patches are merged into the STEP Core Patch so they can be disabled or deleted.
										
				>>EXTENDED PATCH USERS:	Disable Weapon & Armor Fixes/Guard Dialog Overhaul Patch
										Disable Weapon & Armor Fixes/aMidianBorn Skyforge Weapons Patch
										Disable Diverse Priests/Consistent Older People patch
										Disable Diverse Priests/Bring Out Your Dead patch
										Disable Even Better Quest Objectives/Non-Essential Killable Children Patch
										Disable Even Better Quest Objectives/Paarthurnax Dilemma Patch
										Disable Even Better Quest Objectives/DB Forever Misc Patch
										Disable Even Better Quest Objectives/aMidianBorn Skyforge Weapons Patch
										These eight patches are merged into the STEP Extended Patch so they can be disabled or deleted.
		
				>>Bashed Patch users:	Wrye Bash users should make sure that the any of these patches load right before the Bashed Patch. When
										creating the bashed patch, untick the stats checkbox. Create the rest of the bashed patch normally.


STEP: CORE Patch	

	-	Nov. 26 2013 Update:	Now compatible with Weapon and Armor Fixes 4.0, minimal changes were needed.
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

	-	Jan. 07 2014 Update:	Now compatible with Wearable Lanterns 3.0 and Skyrim Coin Replacer Redux instead of Skyrim Coin Replacer.
	-	Nov. 26 2013 Update:	Now compatible with Weapon and Armor Fixes 4.0, minimal changes were needed.
	-	Everything from STEP: CORE Patch carried over
	-	Forward many fixes from USKP not in all three SoS mods on 'Cell' for names and 'Worldspace' for location names and weather data
	-	Forward fixes from USKP to Bring Out Your Dead on 'Cell -> Block 2 -> Sub-Block 1 -> Hall of the Dead -> Persistent' for 6 coffin containers
	-	Resolved conflict between Bring Out Your Dead and The Choice is Yours on NPC 'Perth'
	-	Forward fixes from USKP to Elemental Staves on Weapon 'Staff of Thunderbolt'
			-	Worldspace should be deleted from Elemental Staves plugin do to being completely unnecessary
	-	Forward info count from Dawnguard that conflicted with Dragons Shout with Voice on 'Dialog Topic -> PushRoDah'
	-	Forward any weapon or armor fixes from WAF over USKP since they do the same thing and WAF has stat changes that need to be present in any
		patch where there is a mod farther down that changes the same record
		-	Few exceptions were made:	-	Blade of Woe, USKP adds MaterialDaedric instead of MaterialEbony
			(most of these changes		-	Dawnguard Armor and Weapon descriptions were removed so enchantments could be seen and the bonuses are now
			are also in Core Patch)			a listed in load screens after starting the DG quest
										-	DisallowEnchanting added to some items from USKP that were not in WAF, example Wuuthrad
										-	Object bounds that USKP fixed were forwarded since WAF used the vanilla ones
	-	Forward many fixes from USKP not in More Salt Please on 'Container'
	-	Resolved conflict between SMIM Tern Fix and Ars Metallica - Dragonborn on 'Container' to forward SMIM meshe
	-	Forward many fixes from USKP not in Clanking Armor on 'Armor Addon' to correct Biped Body Template
	-	Resolved Conflict between Blessings - Altar Descriptions and The Choice is Yours on 'Acitvator', forward description change from Altar Descriptions
	-	Forward two fixes from USKP not in Disease Descriptions on 'Spell' for Witbane and Witbane (magicka regen halved)
	-	Forward fix from USKP not in UHFP yet for 'NPC' Gralnach for tint layers and missing item (key to mill).
	-	Merged Diverse Priests-BYOD patch to eliminate plugin
	-	Merged EBQO-Non-Essential Killable Children patch to eliminate plugin
	-	Merged EBQO-Parthunaax Dilemma patch to eliminate plugin
	-	Merged EBQO-DB Forever Misc patch to eliminate plugin
	-	Merged EBQO-AMB Skyforge Weapons patch to eliminate plugin

	
STEP SoS Patch

This patch is unsupported, but is compatible with the unofficial patches and Sounds of Skyrim. This can be used with STEP Core ONLY.
The changes in this patch are included in the STEP Extended Patch.


Install this patch with STEP Core Patch only. Load after the STEP Core Patch.

Forwrad all Worldspace edits from DLC and unofficial pathes
Forward all Cell edits from DLC and unofficial patches
Forward all Region edits from the DLC and unofficial patches
