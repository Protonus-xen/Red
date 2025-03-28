**** Version 0.10.1-RC1 ****
	Updated for 0.98a-RC5.
	Faction:
		Updated for Simulator compatibility.

**** Version 0.10.1 ****
	Updated for 0.97a-RC11.
	Ships:
		Added the Mikanate variant of the Beatrix, the Carolix, carrying an old forgotten friend.
		Added the Mikanate variant of the dreaded Chimiria Heavy Carrier.
		Unneeded Shield Modules for Doris and Dorothyx are completely removed.
		Photon Shields:
			UI overhaul, shield stats are now in tables.
			Shield delay timing logic fixed.
			Stats nerfed but reverts removal Flux-based shields for non-fighter ships.
				Flux Capacity to Shield Strength reduced from 50% to 10%.
				Hull Strength to Shield Strength reduced from 30% to 10%.
				Flux Dissipation to Shield Regeneration reduced from 50% to 30%.
				Flux Capacity to Shield Regeneration added from 0% to 2%.
				Delay time when Damaged and Depleted reduced by roughly 33%.
		Oculian Crystalline Core:
			Phase tag added, as it benefits Oculian Phase ships.
		Oculian Hull:
			Ordinance cost penalty on non-Oculian weapons are reduced from 3/6/10 to 2/4/8.
			Ordinance cost penalty on non-Oculian wings are increased from 10 to 12.
			Energy resistance on hull/armor hit increased from 20% to 30%.
			EMP resistance bonus when Overdriven Clock Systems is installed now correctly reduces to 0.
		Chimly:
			Sprite adjusted.
		Gretly:
			Sprite overhaul.
			Built-in Glint adjusted for another Glint built-in to be added.
			Hullmod now reduces Overload duration by 25%.
			Hull reduced from 650 to 400.
			Top Speed reduced from 180 to 170.
		Gretly Mikanate:
			Hullmod now reduces Overload duration by 33%.
			Hull reduced from 700 to 500.
			Top Speed reduced from 180 to 160.
		Huely:
			Flux Capacity increased from 2200 to 2500.
			Base Supply Maintenance/Repair and Deployment cost reduced from 5 to 4.
		Prily:
			Sprite adjusted.
			Base Supply Maintenance/Repair and Deployment cost reduced from 4 to 3.
		Prily Mikanate:
			Flux Capacity increased from 4000 to 5000.
			Flux Dissipation increased from 350 to 400.
		Chimis:
			Sprite overhaul.
			Modular slot changes:
				1 Medium Synergy, 1 Small Synergy, 4 Small Energy to
				2 Medium Energy, 2 Small Synergy, 2 Small Energy.
			Armor reduced from 200 to 100.
			Ordinance points increased from 45 to 50.
			Base Supply Maintenance/Repair and Deployment cost reduced from 10 to 9.
		Chimis Mikanate:
			Sprite overhaul.
			Added 2 Glint built-ins.
			Modular slot changes:
				1 Medium Synergy, 2 Small Synergy, 4 Small Energy to
				2 Medium Energy, 2 Medium Synergy, 2 Small Energy.
			Armor reduced from 250 to 150.
			Base Supply Maintenance/Repair and Deployment cost increased from 14 to 15.
		Doris:
			Sprite and bounds overhaul.
			Designation changed from Armored Destroyer to Heavy Destroyer.
			Shield Module, and consequently SHIP_WITH_MODULES tag, are removed.
			Modular slot changes:
				4 Medium Energy, 2 Small Synergy to
				1 Large Energy, 2 Medium Synergy.
			Hull increased from 4000 to 4500.
			Armor increased from 550 to 650.
			Flux Capacity increased from 3000 to 5000.
			Flux Dissipation increased from 250 to 350.
			Ordinance points increased from 55 to 60.
		Maximis:
			Sprite and bounds overhaul.
			Modular slot changes:
				2 Large Energy, 4 Small Energy to
				3 Large Energy.
			Fleet point occupancy increased from 5 to 7.
			Hull increased from 3500 to 4000.
			Armor reduced from 450 to 200.
			Flux Capacity increased from 3000 to 6000.
			Flux Dissipation increased from 250 to 350.
			Ordinance points increased from 50 to 60.
			Top Speed reduced from 105 to 90.
			Acceleration reduced from 110 to 60.
			Deceleration reduced from 90 to 45.
			Turn Acceleration reduced from 70 to 45.
			Shield Type changed from FRONT to OMNI.
			Shield Arc reduced from 300 to 180.
			Skeleton Crew increased from 10 to 15.
			Crew Capacity reduced from 15 to 20.
			Base Supply Maintenance/Repair and Deployment cost increased from 10 to 12.
		Sconis:
			Sprite and bounds overhaul.
			Modular slot changes:
				1 Medium Synergy, 5 Small Energy to
				1 Medium Energy, 2 Small Synergy, 7 Energy.
			Fleet point occupancy increased from 5 to 6.
			Armor increased from 350 to 450.
			Ordinance points increased from 55 to 60.
			Skeleton Crew reduced from 15 to 8.
			Crew Capacity reduced from 20 to 15.
			Base Supply Maintenance/Repair and Deployment cost reduced from 7 to 6.
		Sophis:
			Sprite and bounds overhaul.
			Added 2 Small Energy slots at the front of the ship.
			Hull increased from 3000 to 3500.
			Armor reduced from 400 to 350.
			Ordinance points increased from 65 to 70.
			Skeleton Crew reduced from 15 to 10.
			Base Supply Maintenance/Repair and Deployment cost reduced from 9 to 8.
		Lemphis:
			Skeleton Crew reduced from 15 to 10.
		Sophis B:
			Sprite and bounds overhaul.
			Added 2 Small Energy slots at the front of the ship.
			Small Energy turret on the rear is replaced with a Glint built-in.
			Hull reduced from 2500 to 2000.
			Armor reduced from 250 to 150.
			Flux Dissipation reduced from 200 to 150.
		Sophis C:
			Sprite and bounds overhaul.
			Added 2 Small Energy slots at the front of the ship.
			Small Energy turret on the rear is replaced with a Glint built-in.
			Hull increased from 2200 to 2500.
			Armor reduced from 300 to 100.
			Flux Dissipation reduced from 200 to 150.
		Storkis:
			Sprite and bounds overhaul.
			Added 2 Small Energy slots.
			Medium Missile slot is now Synergy.
			Hull increased from 2500 to 3000.
			Armor reduced from 250 to 150.
			Flux Capacity increased from 2000 to 3000.
			Flux Dissipation increased from 100 to 250.
			Top Speed reduced from 150 to 100.
			Acceleration reduced from 125 to 75.
			Deceleration reduced from 100 to 50.
			Maximum Turn Speed increased from 40 to 60.
			Turn Acceleration reduced from 60 to 45.
			Mass increased from 250 to 300.
			Base Supply Maintenance/Repair and Deployment cost increased from 3 to 6.
		Tsundere:
			Sprite adjusted.
			Skeleton Crew reduced from 15 to 10.
			Crew Capacity reduced from 20 to 15.
			Base Supply Maintenance/Repair and Deployment cost increased from 9 to 8.
		Basilix:
			Sprite and bounds overhaul.
			2 Small Energy turrets replaced with 2 Glint built-in.
			Armor reduced from 650 to 350.
			Base Supply Maintenance/Repair and Deployment cost reduced from 18 to 15.
			Flux Capacity reduced from 9000 to 8000.
			Flux Dissipation reduced from 600 to 500.
		Basilix Mikanate:
			Sprite and bounds overhaul.
			Hull increased from 6500 to 7000.
			Armor reduced from 700 to 450.
			Flux Capacity reduced from 10000 to 9000.
			Flux Dissipation reduced from 700 to 600.
			Base Supply Maintenance/Repair and Deployment cost reduced from 26 to 22.
		Beatrix:
			Sprite and bounds overhaul.
			Support Breeze drone ship system replaced with the new Crabcake Frontline.
			Added 1 Glint built-in.
			Modular slot changes:
				2 Medium Missile, 2 Medium Energy, 2 Small Synergy, 2 Small Energy to
				6 Medium Energy, 2 Small Synergy.
			Fleet point cost increased from 10 to 12.
			Armor reduced from 500 to 300.
			Base Supply Maintenance/Repair and Deployment cost increased from 12 to 18.
		Chimex:
			Sprite and bounds overhaul.
			Modular slot changes:
				3 Medium Energy, 4 Small Energy, 2 Small Missile to
				3 Medium Synergy, 3 Medium Energy, 4 Small Energy.
			Hull increased from 5000 to 6000.
			Armor reduced from 450 to 300.
			Ordinance points increased from 90 to 100.
		Chimex Mikanate:
			Sprite and bounds overhaul.
			Added 3 Glint and 1 Breeze Mikanate (H) wing built-ins.
			Modular slot changes:
				2 Medium Energy, 2 Medium Missile, 5 Small Energy to
				3 Medium Synergy, 3 Medium Energy, 6 Small Energy.
			Fleet point cost increased from 15 to 18.
			Hull increased from 5500 to 7000.
			Armor reduced from 450 to 350.
			Ordinance points increased from 110 to 125.
			Mass increased from 800 to 850.
			Base Supply Maintenance/Repair and Deployment cost increased from 22 to 25.
		Dorothyx:
			Sprite and bounds overhaul.
			Designation changed from Armored Cruiser to Heavy Cruiser.
			Shield Module, and consequently SHIP_WITH_MODULES tag, are removed.
			Modular slot changes:
				1 Large Energy, 2 Medium Energy, 5 Small Synergy, 2 Small Energy to
				2 Large Energy, 5 Small Synergy, 11 Small Energy.
			Fleet point cost increased from 13 to 16.
			Armor reduced from 900 to 700.
			Flux Capacity increased from 7000 to 9000.
			Flux Dissipation increased from 450 to 600.
			Ordinance points increased from 100 to 120.
			Acceleration reduced from 100 to 40.
			Deceleration reduced from 75 to 30.
			Maximum Turn Speed reduced from 60 to 45.
			Turn Acceleration reduced from 40 to 30.
			Base Supply Maintenance/Repair and Deployment cost increased from 20 to 25.
		Ignix:
			Sprite and bounds overhaul.
			Designation changed again from Missile Carrier to Cruiser.
			Mollusc Drone ship system replaced with the new Crabcake Drone.
			2 Glint built-ins from the front are removed.
			Modular slot changes:
				2 Large Synergy, 3 Medium Energy, 1 Medium Missile to
				3 Large Missile, 2 Small Synergy.
			Ordinance points reduced from 100 to 60.
			Flux Dissipation increased from 200 to 300.
			Top Speed increased from 90 to 100.
			Base Supply Maintenance/Repair and Deployment cost reduced from 16 to 15.
		Nimbyx:
			Sprite and bounds overhaul.
			Built-in Breeze wing removed.
			Modular slot changes:
				1 Medium Energy, 3 Small Energy to
				3 Medium Energy, 1 Small Synergy, 6 Small Energy.
			Ordinance points increased from 60 to 75.
			Armor reduced from 300 to 200.
		Amina:
			Sprite and bounds overhaul.
			Modular slot changes:
				2 Large Synergy, 3 Large Energy, 8 Medium Energy, 4 Small Missiles to
				1 Large Synergy, 1 Large Energy, 2 Medium Synergy, 10 Medium Energy, 8 Small Missiles.
			Fleet point cost increased from 26 to 28.
			Armor reduced from 1200 to 1000.
			Flux Capacity reverted from 12000 to 15000.
			Flux Dissipation reduced from 800 to 1000.
			Base Supply Maintenance/Repair and Deployment cost increased from 40 to 45.
		Chimaria:
			Sprite adjusted.
			Added 1 Glint built-in.
			Modular slot changes:
				2 Large Synergy, 5 Medium Energy, 4 Small Synergy to
				2 Large Synergy, 7 Medium Energy, 6 Small Synergy.
			Hull increased from 8000 to 9000.
			Armor reduced from 700 to 450.
			Flux Capacity increased from 8000 to 10000.
			Ordinance points increased from 160 to 180.
			Shield Upkeep slightly reverted from 0.3 to 0.4.
			Base Supply Maintenance/Repair and Deployment cost reduced from 42 to 40.
			Modules:
				Hull increased from 3000 to 4000.
				Armor reduced from 500 to 300.
				Flux Dissipation reduced from 400 to 300.
		Etna:
			Sprite adjusted.
			Added 1 Glint built-in.
			Modular slot changes:
				2 Large Energy, 3 Medium Energy, 3 Medium Synergy, 2 Small Synergy to
				2 Large Synergy, 5 Medium Energy, 3 Medium Synergy, 2 Small Synergy.
			Hull increased from 7000 to 8000.
			Armor reduced from 850 to 400.
			Ordinance points increased from 150 to 165.
			Base Supply Maintenance/Repair and Deployment cost increased from 32 to 35.
		Nadia:
			Sprite adjusted.
			Added 2 Glint built-ins at the front.
			Ion Cruise Jets ship system is reverted to Mollusc Drone. (+ Mi)
			Fleet point cost increased from 22 to 25.
			Base Supply Maintenance/Repair and Deployment cost increased from 38 to 45.
			Armor reduced from 1000 to 650.
			Module:
				Hull increased from 2000 to 3000.
				Armor reduced from 750 to 600.
				Flux Capacity increased from 4000 to 5000.
		Nadia Mikanate:
			Ion Cruise Jets ship system is reverted to Mollusc Drone.
			Fleet point cost increased from 28 to 32.
			Base Supply Maintenance/Repair and Deployment cost increased from 44 to 50.
			Armor reduced from 1100 to 700.
			Module:
				Hull increased from 2000 to 3500.
				Armor reduced from 750 to 600.
				Flux Capacity increased from 5000 to 6000.
		Dulcena:
			Sprite shrunked and adjusted.
			Removed Integrated Oculian Optics hullmod built-in.
			Added 1 Glint built-in.
			Modular slot changes:
				2 Large Synergy, 7 Large Energy, 2 Medium Synergy, 13 Medium Energy to
				2 Large Synergy, 5 Large Energy, 4 Medium Synergy, 13 Medium Energy, 10 Small Energy.
			Dulcena Array now provides 300/200/100 base range to Small/Medium/Large projectile weapons.
			Flux Efficiency for Energy weapons increased from 10% to 25%.
			Ordinance points increased from 230 to 250.
			Flux Capacity increased from 18000 to 24000.
			Flux Dissipation increased from 1000 to 1200.
			Shield Efficiency reduced from 0.8 to 1.
			Top Speed increased from 40 to 50.
			Acceleration increased from 15 to 25.
			Deceleration increased from 10 to 15.
			Maximum Turn Speed increased from 9 to 12.
			Turn Acceleration increased from 4 to 5.
			Mass reduced from 6500 to 6000.
			Skeleton Crew reduced from 200 to 80.
			Crew Capacity reduced from 250 to 160.
		Pandora:
			Sprite adjusted.
			Designation changed again from Dreadnought Carrier to Dreadcarrier.
			Added 12 Glint built-ins.
			Added 4 Small Synergy turrets.
			Base Price increased from 550000 to 700000.
			Fleet point cost increased from 45 to 50.
			Armor reduced from 1150 to 1000.
			Ordinance points increased from 230 to 250.
			Base Supply Maintenance/Repair and Deployment cost increased from 68 to 80.
			Side Sections:
				Hangar slots increased from 3 to 4.
				Ordinance points increased from 70 to 80.
	Weapons:
		Sprite overhaul for most of the weapons, focusing more on retaining their compact, spherical shapes.
		Added Retina and Tina, downscaled variants of the Kurtina as basic Oculian weapons.
		Added the original triple-barreled Luna cannon.
			Does not replace the previous Luna cannon on Galalixia.
			Mikanate recolor will come soon for the 0.98 update.
		Glint:
			Damage per shot increased from 56 (120) to 60 (128).
			Flux generation reduced from 35 (175) to 30 (150).
		Gleam:
			Added PD tag.
			Damage per shot reduced from 316 (500) to 240 (411).
			Flux generation reduced from 200 (1000) to 105 (420).
			Charge down reduced from 1.3 to 1.0.
			Burst Size increased from 0.2 to 0.25.
			Burst delay reduced from 0.5 to 0.25.
			Turn rate increased from 40 to 60.
		Gistal:
			Added PD and ANTI_FTR tags.
			Damage per shot increased from 854 (1350) to 720 (982).
			Flux generation reduced from 600 (3000) to 270 (954).
			Burst Size increased from 0.2 to 0.3.
			Burst delay reduced from 1.5 to 0.4.
			Turn rate increased from 15 to 30.
		Shiredain:
			Damage per shot increased from 300 to 350.
			Flux per shot increased from 225 to 245.
			Ammo reduced from 50 to 40.
			Ammo per second added from 0 to 0.1.
			Ammo reload sized added from 0 to 10.
			Charge down time reduced from 4 to 3.25.
		Kea:
			Flux per shot reduced from 30 to 15.
		Kaina:
			Charge up time reduced from 0.67 to 0.6.
			Charge down time increased from 0.83 to 1.
			Flux per shot reduced from 60 to 30.
		Katalina:
			Flux per shot reduced from 90 to 50.
		Prima:
			EMP damage per shot added from 0 to 10.
			Charge up time increased from 0.125 to 0.15.
		Stredia:
			EMP damage per shot added from 0 to 15.
			Charged EMP damage per shot increased from 100 to 120.
		Leia:
			EMP damage per shot added from 0 to 10.
		Manndie:
			EMP damage per shot added from 0 to 20 (10).
			Burst Shot EMP damage per shot added from 0 to 20.
		Freya:
			Flux per shot reduced from 290 to 240.
			Ammo per second reduced from 2 to 1.5.
		Kurtina:
			No longer has PD and ANTI_FTR tags.
		Flandrey Beam Cannon:
			Flux per second reduced from 840 to 525.
		(Old) "Luna" Cannon:
			Renamed to Serlena Blaster.
				Since weapon is typically built-in to the Galalixia, nothing has changed.
		Pixel+:
			Ammo increased from 8 to 10.
			Charge down time reduced from 10 to 6.
		Pixel++:
			Charge down time reduced from 10 to 8.
	Wings:
		Breeze:
			Flux Capacity reduced from 100 to 60.
			Flux Dissipation increased from 25 to 30.
		Breeze Mikanate:
			Flux Capacity reduced from 150 to 100.
			Flux Dissipation increased from 35 to 40.
		Breeze Elite:
			Flux Capacity reduced from 150 to 75.
		Breeze Superelite:
			Flux Capacity reduced from 200 to 125.
		Kaleido:
			Flux Capacity increased from 300 to 350.
		Kaleido Elite:
			Flux Capacity increased from 500 to 600.
			Flux Dissipation increased from 120 to 150.
			Removed 1 Kea.
		Kaleido Mikanate:
			Flux Capacity increased from 600 to 750.
			Flux Dissipation increased from 150 to 200.
			Added 1 Deci Pixie.
		Cancer Mikanate:
			Kilopixel range increased to match the similar patterns made by its smaller counterparts.
		Tick Basic/Elite/Mikanate:
			Shield removal reverted, but with minor changes between tiers.
			Basic:
				Shield Arc reduced from 150 to 90.
			Elite:
				Armor increased from 100 to 150.
				Shield Arc reduced from 150 to 120.
				Shield Efficiency increased from 0.9 to 0.8.
			Mikanate:
				Armor increased from 150 to 200.
				Shield Efficiency increased from 0.9 to 0.7.

**** Version 0.10.0-RC2 ****
	Campaign:
		Nexerelin:
			Removed the Orbital Assembly Matrix from IndustryClassDefs, since comprehension issue.
			(Yes, this is the smallest, oldest but actually the most irritating issue RED has experienced in its history)

**** Version 0.10.0-RC1 ****
	Weapons:
		Stredia:
			Added null check for errors.

**** Version 0.10 ****
	Shield Overhaul Update
	Campaign:
		Atalie Pax:
			Dwarf star is larger.
			Orbits are slightly larger.
		Atalie II-B:
			Planet size increased from 4 to 5.
			Added Heavy Batteries and Commerce.
			Patrol HQ, Waystation and Light Industry have Gamma Cores.
			Orbital Station upgraded to Battlestation.
		Atalie III-A:
			No Atmosphere condition replaced with Thin Atmosphere.
			Mild Climate added.
			Mining and Refining Alpha Cores replaced with Beta Cores.
			Fuel Production loses Synchrotron but gets an Alpha Core.
			Removed Waystation but Spaceport is upgraded to Mega Port.
		Haelim II Minor:
			Now Barren-Bombarded.
			Very Cold condition replaced with Thin Atmosphere.
			Has Ground Defenses with Gamma Core.
			Mining and Population has Gamma Cores.
		Orbital Assembly Matrix:
			Ground Defense bonus increased from 10% to 20%.
	Ships:
		Added the Photon Shielding:
			A permanent skinshield that passively protects Oculian ships from damage.
			Scales with Hull and Flux Capacity for Health and Dissipation for Regeneration.
			Most ships with shields will have them removed, with stats changed to reflect it. 
				Usually around speed as it influences (or the lack of) Flux majorly.
			Variants with Hardened Shields are changed.
			Resistances are the same as the old shields but Energy resistance is increased to 80%.
			EMP damage does affect these shields.
		Oculian Hull:
			Added Non-shield Energy resistance by 20%.
			Removed PD weapon AI "bonus" due to redundancy and forced usage.
			EMP resistance increased from 25% to 50%.
			Non-shield Beam resistance increased from 10% to 20%.
			Supply Cost for Maintenance and Repair reduced from 33% to 40%.
			Mikanate variants will have reduced Supply costs as well by 10%.
		Overdriven Clock Systems:
			Removed Shield movement bonus removal. Proxied from Oculian Hull.
		Oculian Crystalline Core:
			Can now be installed without true shields.
		Mikanate Core variants:
			Will now refuse to show up in the Hullmod tab since they are not supposed to be seen.
		Chimly:
			Top Speed reduced from 140 to 120.
			Acceleration reduced from 180 to 150.
			Deceleration reduced from 140 to 120.
			Maximum Turn Speed reduced from 100 to 90.
			Turn Acceleration reduced from 150 to 120.
			(Mi):
				Flux Capacity increased from 2000 to 3000.
		Prily:
			Top Speed reduced from 240 to 200.
			Acceleration reduced from 270 to 240.
			Deceleration reduced from 200 to 160.
			Maximum Turn Speed reduced from 175 to 150.
			Turn Acceleration reduced from 350 to 300.
			(Mi):
				Flux Capacity increased from 3000 to 4000.
				Top Speed reduced from 200 to 180.
				Acceleration reduced from 220 to 200.
				Turn Acceleration reduced from 250 to 240.
		Chimis:
			Flux Capacity reduced from 3600 to 3500.
			Top Speed reduced from 90 to 80.
			Acceleration reduced from 105 to 90.
			Deceleration reduced from 90 to 70.
			Turn Acceleration reduced from 50 to 40.
			(Mi):
				Flux Capacity increased from 4000 to 4500.
				Top Speed reduced from 90 to 70.
				Acceleration reduced from 95 to 80.
				Deceleration reduced from 80 to 60.
				Turn Acceleration reduced from 50 to 40.
		Sophis:
			Top Speed reduced from 150 to 140.
			Acceleration reduced from 150 to 140.
			Deceleration reduced from 120 to 105.
			Turn Acceleration reduced from 55 to 50.
		Sconis:
			Ion Burst Drive ship system is replaced with Ion Cruise Jets.
			Flux Capacity increased from 3000 to 4000.
			Top Speed reduced from 180 to 160.
			Acceleration reduced from 160 to 140.
			Deceleration reduced from 140 to 125.
		Lemphis:
			Flux Capacity increased from 5000 to 6000.
			Top Speed reduced from 160 to 150.
			Acceleration reduced from 160 to 150.
			Deceleration reduced from 130 to 120.
			Maximum Turn Speed reduced from 70 to 60.
			Turn Acceleration reduced from 60 to 50.
		Sophis B/C:
			Top Speed reduced from 110 to 80.
			Acceleration reduced from 90 to 70.
			Deceleration reduced from 90 to 70.
			Maximum Turn Speed reduced from 50 to 45.
			Turn Acceleration reduced from 35 to 30.
		Basilix:
			Hull reduced from 7000 to 6000.
			Flux Dissipation reduced from 650 to 600.
			(Mi):
				Hull reduced from 8000 to 6500.
		Ignix:
			Flux Capacity increased from 5000 to 8000.
		Amina:
			Flux Capacity reduced from 15000 to 12000.
			Flux Dissipation reduced from 1000 to 800.
		Nadia:
			Mollusc Drone ship system is replaced with Ion Cruise Jets.
			Flux Capacity reduced from 12000 to 10000.
			Flux Dissipation reduced from 800 to 700.
			Module Shield Arc increased from 60 to 90.
			(Mi):
				Mollusc Drone ship system is replaced with Ion Cruise Jets.
				Flux Capacity reduced from 14000 to 12000.
				Flux Dissipation reduced from 900 to 800.
				Module Shield Arc increased from 60 to 90.
		Pandora:
			Flux Capacity reduced from 15000 to 12000.
			Flux Dissipation reduced from 900 to 800.
		Dulcena:
			Retains its Shield.
			Fortress Shield ship system is replaced with Accelerated Energy Feed.
			Base Price increased from 640000 to 800000.
			Flux Capacity reduced from 24000 to 18000.
			Flux Dissipation reduced from 1200 to 1000.
			Base Supply Maintenance/Repair and Deployment cost increased from 65 to 80.
	Drones:
		Mollusc:
			Shield removed.
			(Mi):
				Shield removed.
				Hull increased from 100 to 150.
				Flux Capacity increased from 250 to 300.
				Flux Dissipation increased from 75 to 150.
	Wings:
		All but Kaleido and Loach wing variants will lose their shields in place for Refractive Shielding.
			This change will remove the unneeded shield logic for fighters making Oculian fights significantly less laggy.
			Will use 100% of Flux Capacity and Dissipation for shield stats.
		Breeze (and Mi):
			Roles have been swapped, normal Breezes are now Fighters.
		Elite Breeze (and Mi):
			Removed the mysterious culprit Advanced Optics hullmod for triggering a warning sound whenever the wings are used.
			Roles have been swapped, Elite Breezes are Interceptors.
		Tick (and Mi):
			Role is switched to Interceptor.
	Weapons:
		Glint:
			Sound volume reduced again.
			

**** Version 0.9.3 ****
	Updated for version 0.96a-RC9.
	Campaign:
		Oculian Station:
			Flux stats have been shuffled to make gaps more pronounced and compensate with the general efficiency buffs on weapons.
			Shields are standardized to the base value as shield resistance is moved towards resisting beam weapons than just energy.
			Shield Modules are changed towards being high cap/low vent to have them behave more like armor than shields.
			Pillar Guard:
				Flux Capacity increased from 4000 to 5000.
				Flux Dissipation reduced from 400 to 250.
				Shield Efficiency reduced from 0.8 to 1.
				Ordinance Points reduced from 200 to 50.
			Weapons Platform:
				Flux Capacity increased from 12000 to 14000.
				Flux Dissipation reduced from 1000 to 700.
				Shield Efficiency reduced from 0.8 to 1.
			Basic Ring Segment:
				Flux Capacity increased from 6000 to 9000.
				Flux Dissipation reduced from 750 to 450.
				Shield Efficiency reduced from 0.8 to 1.
			Star Fortress Ring Segment:
				Flux Capacity increased from 8000 to 12000.
				Flux Dissipation reduced from 1000 to 800.
				Shield Efficiency reduced from 0.8 to 1.
			Shield Module:
				Flux Capacity increased from 10000 to 18000.
				Flux Dissipation reduced from 1000 to 300.
				Shield Efficiency reduced from 0.8 to 1.
				Ordinance Points reduced from 200 to 50.
			Hangar Module:
				Flux Capacity increased from 6000 to 7000.
				Flux Dissipation reduced from 750 to 350.
				Shield Efficiency reduced from 0.8 to 1.
			Hangar Command:
				Flux Capacity increased from 9000 to 10000.
				Flux Dissipation reduced from 900 to 500.
				Shield Efficiency reduced from 0.8 to 1.
	Ships:
		Reduced Engine sound volume slightly more across the board.
		Autonomous Drone:
			Now displays Sensor strength bonus.
			Added Weapon/Engine repair speed bonus by mathematically 33% (-24.82~% = 1 / (1 + bonus)).
			Added Sensor profile reduction by 10.
			Reduced Sensor strength from 20 to 10.
		Oculian Hull:
			Added Hull and Armor damage resistance against Beam weapons by 10%.
			Added Shield resistance against Beam weapons by 25%.
			Shield damage taken from Energy type reduced from 25% to 15%.
		Kitted Gretly Buster:
			When S-modded, increases death explosion further, also increases flux capacity and shield efficiency.
		Overdriven Clock Systems:
			When S-modded, reduces penalties significantly and gives a flatout hull and armor damage resistance.
		Overdriven Clock Systems:
			When S-modded, reduces penalties damage penalty and increases beam damage regardless of faction.
		Sconis:
			Medium Energy mount is changed to Medium Synergy.
			Flux Capacity increased from 2500 to 4000.
			Flux Dissipation reduced from 300 to 200.
			Ordinance points increased from 50 to 55.
			Shield Efficiency increased from 0.9 to 0.7.
		Tsundere:
			Armor reduced from 200 to 150.
			Flux Capacity increased from 4000 to 5000.
		Basilix:
			Top Speed increased from 75 to 80.
			Acceleration reduced from 75 to 70.
			Maximum Turn Speed increased from 50 to 60.
			(Mi):
				Fleet point cost reduced from 20 to 18.
				Top Speed increased from 75 to 80.
				Acceleration reduced from 75 to 70.
				Maximum Turn Speed increased from 50 to 60.
		Chimex:
			Armor reduced from 600 to 450.
			Flux Capacity increased from 4500 to 6000.
			(Mi):
				Fleet point cost reduced from 18 to 15.
				Armor reduced from 600 to 450.
				Flux Capacity increased from 5500 to 7500.
		Dorothyx:
			Flux Capacity increased from 6000 to 7000.
			Top Speed reduced from 65 to 50.
			Acceleration increased from 55 to 100.
			Deceleration increased from 30 to 75.
			Maximum Turn Speed increased from 25 to 60.
			Turn Acceleration increased from 20 to 40.
		Ignix:
			CARRIER and COMBAT tags removed.
			Engine count increased from 3 to 7.
			Hull reduced from 6000 to 4000.
			Armor reduced from 600 to 350.
			Flux Capacity increased from 4000 to 5000.
			Flux Dissipation reduced from 250 to 200.
			Shield Arc increased from 240 to 300.
			Shield type changed from Omni to Front.
			Shield Efficiency increased from 0.9 to 0.7.
			Top Speed increased from 60 to 90.
			Acceleration increased from 45 to 75.
			Deceleration reduced from 35 to 45.
			Maximum Turn Speed increased from 40 to 60.
			Turn Acceleration increased from 20 to 30.
		Evalyx:
			Top Speed increased from 70 to 80.
			Phase Upkeep generation reduced from 0.06 to 0.03.
		Amina:
			Flux Capacity increased from 14000 to 15000.
			Top Speed increased from 70 to 80.
			Acceleration reduced from 60 to 40.
			Deceleration reduced from 40 to 30.
			Maximum Turn Speed increased from 50 to 60.
		Chimaria:
			Flux Dissipation reduced from 650 to 500.
			Shield Upkeep reduced from 0.5 to 0.3.
		Etna:
			CARRIER, COMBAT and NO_AUTO_ESCORT tags removed.
		Nadia (Mi):
			Fleet point cost reduced from 32 to 28.
		Utena:
			Flux Dissipation reduced from 1000 to 800.
			Titanic Phase Columns:
				Added Energy damage resistance by 10%.
				Speed bonus increased from 50 to 60. (Manueverability increased accordingly)
		Pandora:
			Designation changed from Flagship to Dreadnought Carrier.
		Dulcena:
			Base Supply Maintenance/Repair cost reduced from 74 to 65.
	Wings:
		Loach (and Mi):
			Phase Initial Cost generation increased from 0.02 to 0.08.
			Phase Upkeep generation reduced from 0.04 to 0.03.
	Weapons:
		Glint:
			Flux generation reduced from 40 (200) to 35 (175).
		Pirouette:
			Flux per shot reduced from 25 to 15.
		Fouette:
			Flux per shot reduced from 30 to 25.
		Shiredain:
			Flux per shot reduced from 250 to 225.
		Blita:
			Damage per shot reduced from 60 to 50.
			Flux per shot reduced from 40 to 25.
			Cooldown per shot increased from 0.25 to 0.33.
			Spread is removed and shots have perfect accuracy.
		Gleam:
			Flux generation reduced from 140 (1400) to 100 (1000).
		Prima:
			Damage per shot reduced from 80 to 75.
			Flux per shot reduced from 50 to 45.
			Charge up delay reduced from 0.15 to 0.125.00).
		Glistal:
			Flux generation reduced from 300 (4500) to 200 (3000).
		Kurtina:
			Damage increased from 240 to 270.
			Flux per second reduced from 150 to 135.
		Vira:
			Flux per shot reduced from 60 to 40.
			Cooldown per shot increased from 0.125 to 0.2.
			Spread is removed and shots have perfect accuracy.
		Pixie:
			Flux per shot reduced from 150 to 130.
		Fairy:
			Flux per shot reduced from 200 to 180.
		Freya:
			Flux per shot reduced from 310 to 290.
		Nicor:
			Flux per shot reduced from 180 to 160.
		Flandrey Beam Cannon:
			Flux per second reduced from 945 to 840.

**** Version 0.9.2b ****
	Campaign:
		Forcefully deprecated Arc Mother's Cognition skill to prevent randomized distribution.
	Ships:
		Oculian Chemical Core:
			Unintended stacking beam bonuses removed. Along with associated Mikanate variant and hybrids. (Yes, this is a nerf to an unintended effect, that leaves Crystalline core very underused)
			Description wording changed to reflect that hullmod generally improves Energy weapons.
		Oculian Crystalline Core:
			Can now be equipped on Oculian Phase ships, increasing Phase efficiency and reducing Cooldown time. Mikanate and hybrids receive this bonus.
			Phase ships now cancel the top speed penalty.
			Now reduces Beam Flux generation by 15% (20% for Mikanate).
		Mikanate Pulse Core:
			Time script now uses the matured Jandor Time Reactor script to determine conditions and avoid buggy time events. Hopefully.
			
**** Version 0.9.2a ****
	Campaign:
		Nexerelin:
			Fixed forgotten ID change to Orbital Matrix for industryClassDefs.
	Ships:
		Evalyx:
			Lossless Void Carriage:
				Removed the outdated description to already changed effect. Author issue.
			Change the Assault variant using an impossible core.
			Base Supply Maintenance/Repair cost increased from 24 to 36.
			
**** Version 0.9.2 ****
	Campaign:
		Ocutek Pirate Package manually seperated to the Ocutek Pirates submod to prevent the effectively non-existent blueprint from dropping.
		Oculians receive their own naming theme with their people. Serial number for Female and Auxiliary number for Male(Robot).
		Relations changed for the corresponding factions:
			Added a bare minimum catch logic for Hostile and Vengeful relations.
			(HMI) Oculians are now hostile to Mess variations.
			Player from Vengeful to Suspicious.
			Sindrian Diktat from default Inhospitable to Favorable.
			Luddic Path from default to Vengeful.
			Luddic Church from default to Hostile.
		Star systems and planets associated are now uniquely prefixed.
		Oculian Cookies:
			Updated to current commodities system.
		Atalie Pax:
			Atalie II:
				Now a Barren-desert World.
				Extreme Heat planet condition replaced with Hot.
				Mild Climate planet condition added.
				Market Size increased from 4 to 5.
			Adalie:
				EI is added. Dialogue and Image not included, yet.
				Organics changed from Abundant to Common.
				Mining has a Gamma Core.
				Added unique Heavy Industry called Orbital Assembly Matrix, replacing Orbital Works that does not require a Nanoforge to produce quality ships.
				Population and Oculian Bakery Complex no longer have Alpha Cores.
			Atalie III-a:
				Extreme Cold planet condition removed.
		Haelim:
			Haelim I:
				Mild Climate planet condition added.
			Darla:
				Now an Arid planet and has Habitable planet condition.
			Haelim IIa:
				Inimical Biosphere planet condition removed.
		Doctrine changed, from 1-3-3 to 4-1-2.
		Added missing generic music to encounters and other things.
		Nexerelin:
			Diplomacy:
				Is no longer Ideological.
				Diplomacy is increased from +0.1 to +0.25.
			Basic blueprint package is given immediately if starting faction.
	Ships:
		Added the Evalyx Phase Cruiser, a Mikanate Phase cruiser with a dependable logistics capability and a powerful loadout.
		Added the Dulcena Dreadnought, a massive flagship that focuses in direct frontal combat.
		Added Oculian Optimized Optics, a sidegrade to Advanced Optics that increases base range but at a cost of shield damage.
		Mikanate ships and some regulars are now only sold in the Military market.
		Oculian Hull:
			Description has been overhauled for a more readable overview.
			The following changes removes redundant computations with regards to logistics, that would otherwise overcomplicate the descriptions:
				Supply Maintenance/Recovery reduction increased from 25% to 33%.
				Supply cost reduction removed if Mikanate Overhaul is added.
				Base Supply costs for every ship is adjusted accordingly for Deployment cost purposes that impact battle size.
			Can no longer allow Advanced Optics.
		Mikanate Overhaul:
			Description has been overhauled for a more readable overview.
			Supply Maintenance/Recovery penalty increase removed.
			Combat Readiness decay depletes 100% faster.
		All Oculian Cores:
			Description has been overhauled for a more readable overview.
		Oculian Crystalline Core:
			Top Speed reduction is now a percentage. Zero Flux Speed is also normalized. (+ subsequent Mikanate combinations)
			Shield damage reduction bonus reverted from 20% to 15%. (+ subsequent Mikanate combinations)
		Mikanate Crystalline Core:
			Top Speed reduction is now a percentage. Zero Flux Speed is also normalized.
			Shield damage reduction bonus reduced from 35% to 25%.
			Top Speed reduction penalty reduced from 30% to 25%.
		Oculian Pulse Core:
			Removed the unmentioned refit time penalty.
			Replacement Recovery rate penalty of -33% is added.
		Chimly:
			Rugged Construction hullmod added. (+ Mi)
		Gretly:
			Fleet Points reduced from 3 to 2.
			Gretly Reassembly Contigency hullmod added, an improved variation of Rugged Construction.
			Hull increased from 500 to 650.
			Top Speed reduced from 200 to 180.
		Gretly (Mi):
			Gretly Reassembly Contigency hullmod added.
			Hull increased from 600 to 700.
		Huely:
			Rugged Construction hullmod added.
			Added 1 Small Synergy hardpoint.
			Base Supply Maintenance/Repair cost increased from 3 to 5.
		Prily:
			Fleet Points reduced from 3 to 2.
			Rugged Construction hullmod added. (+ Mi)
			Top Speed reduced from 240 to 200.
			Acceleration reduced from 270 to 240.
		Chimis:
			Acceleration increased from 70 to 105.
			Deceleration increased from 55 to 90.
			Base Supply Maintenance/Repair cost increased from 7 to 10.
			Mi:
				Acceleration increased from 60 to 95.
				Deceleration increased from 55 to 80.
				Base Supply Maintenance/Repair cost increased from 9 to 14.
		Doris:
			Acceleration increased from 60 to 90.
			Deceleration increased from 50 to 70.
			Base Supply Maintenance/Repair cost increased from 8 to 11.
		Lemphis:
			Acceleration increased from 125 to 160.
			Deceleration increased from 100 to 130.
			Base Supply Maintenance/Repair cost increased from 8 to 14.
		Maximis:
			Acceleration increased from 90 to 110.
			Deceleration increased from 75 to 90.
			Base Supply Maintenance/Repair cost increased from 6 to 10.
		Sconis:
			Acceleration increased from 140 to 160.
			Deceleration increased from 125 to 140.
			Base Supply Maintenance/Repair cost increased from 5 to 7.
		Sophis:
			Acceleration increased from 120 to 150.
			Deceleration increased from 100 to 120.
			Base Supply Maintenance/Repair cost increased from 6 to 9.
		Sophis B/C:
			Fleet Points reduced from 5 to 4.
			Base Supply Maintenance/Repair cost increased from 2 to 4.
		Storkis:
			Acceleration increased from 90 to 125.
			Deceleration increased from 80 to 100.
		Tsundere:
			Sprite adjustments. Some weapon slots have been moved.
			Designation changed from Fast Destroyer to Destroyer.
			Acceleration increased from 110 to 125.
			Deceleration increased from 90 to 100.
			Shield Efficiency increased from 0.9 to 0.8.
			Base Supply Maintenance/Repair cost increased from 7 to 9.
		Beatrix:
			Designation changed from Heavy Gunport to Monitor.
			Fleet Points reduced from 12 to 10.
			Hull increased from 3500 to 5000.
			Maximum Turn Speed reduced from 25 to 40.
			Turn Acceleration reduced from 15 to 25.
		Basilix:
			Sprite adjustments. (+ Mi)
			Hangar is removed, respective tags for the carrier role is removed while Quantix Core can still take effect. (+ Mi)
			2 built-in Glints added. (+Mi)
			Hull increased from 5000 to 7000.
			Armor increased from 550 to 650.
			Ordinance points increased from 100 to 110.
			Maximum Turn Speed increased from 20 to 50.
			Turn Acceleration reduced from 20 to 30.
			Base Supply Maintenance/Repair cost increased from 14 to 18.
			Mi:
				Hull increased from 6000 to 8000.
				Armor increased from 600 to 700.
				Ordinance points increased from 120 to 130.
				Maximum Turn Speed increased from 20 to 50.
				Turn Acceleration reduced from 20 to 30.
				Mass reduced from 1000 to 900.
				Base Supply Maintenance/Repair cost increased from 22 to 26.
		Chimex:
			Fleet Points reduced from 12 to 11.
			Hull increased from 4000 to 5000.
			Base Supply Maintenance/Repair cost increased from 15 to 18.
			Acceleration increased from 40 to 50.
			Deceleration reduced from 60 to 40.
			Turn Acceleration reduced from 40 to 35.
			Mass increased from 650 to 750.
			Mi:
				Fleet Points reduced from 20 to 18.
				Hull increased from 5000 to 5500.
				Acceleration increased from 40 to 50.
				Deceleration reduced from 60 to 40.
				Turn Acceleration reduced from 40 to 35.
				Base Supply Maintenance/Repair cost increased from 20 to 22.
				Mass increased from 650 to 800.
		Dorothyx:
			Redesigned to fit its in-lore saucer build.
			Shield module overhauled to be vulnerable from 2 lateral sides to 4 corners.
			Modular slot changes:
				From 1 Large Energy, 2 Medium Energy, 2 Small Energy, 4 Small Synergy, 3 built-in Glints
				To 1 Large Energy, 2 Medium Energy, 2 Small Energy, 5 Small Synergy, 4 built-in Glints.
			Large Energy turret moved to the center, while allowing 360 angle coverage.
			Fleet Points increased from 11 to 13.
			Hull increased from 4000 to 7000.
			Flux Capacity increased from 5000 to 6000.
			Flux Dissipation increased from 400 to 450.
			Top Speed reduced from 70 to 65.
			Base Supply Maintenance/Repair cost increased from 16 to 20.
			Shield Module:
				Armor reduced from 750 to 500.
				Flux Capacity reduced from 5000 to 4000.
				Flux Dissipation reduced from 250 to 200.
				Shield Type changed from Front to Omni.
		Ignix:
			Sprite adjustments.
			Hangars are removed, respective tags for the carrier role is removed while Quantix Core can still take effect.
			Fleet Points increased from 11 to 12.
			Hull increased from 4500 to 6000.
			Armor reduced from 850 to 600.
			Ordinance points increased from 90 to 100.
			Flux Capacity increased from 3000 to 4000.
			Flux Dissipation increased from 200 to 250.
			Top Speed reduced from 70 to 60.
			Acceleration reduced from 70 to 45.
			Maximum Turn Speed increased from 20 to 40.
			Turn Acceleration increased from 10 to 20.
			Base Supply Maintenance/Repair cost increased from 11 to 16.
		Nimbyx:
			Armor reduced from 400 to 300.
			Flux Capacity increased from 4000 to 6000.
			Maximum Turn Speed increased from 10 to 20.
			Turn Acceleration increased from 10 to 15.
		Amina:
			Sprite adjustments.
			Designation changed from Warship to Fast Battleship.
			Added Integrated Oculian Optics hullmod.
			Modular slot changes:
				From 2 Large Synergy, 3 Large Energy, 4 Medium Synergy, 2 Small Energy, 4 Small Synergy, 6 built-in Glints
				To 2 Large Synergy, 3 Large Energy, 4 Medium Synergy, 4 Medium Energy, 4 Small Missile, 14 built-in Glints.
			All 3 Hangars are removed, respective tags for the carrier role is removed while Quantix Core can still take effect.
			Fleet Points reduced from 28 to 26.
			Flux Capacity increased from 12000 to 14000.
			Flux Dissipation increased from 900 to 1000.
			Top Speed increased from 50 to 70.
			Acceleration increased from 35 to 60.
			Deceleration increased from 15 to 40.
			Maximum Turn Speed increased from 15 to 25.
			Turn Acceleration increased from 7 to 12.
			Shield Angle reduced from 360 to 300.
			Shield upkeep reduced from 0.5 to 0.3.
			Skeleton Crew increased from 65 to 90.
			Maximum Crew increased from 80 to 120.
			Base Supply Maintenance/Repair cost reduced from 50 to 40.
		Etna:
			Sprite adjustments. Some mounts have been moved.
			Designation changed from Fast Battleship to Battlecruiser.
			Temporal Overclock:
				Time Flow multiplier reduced from 5x to 4x.
				Charge up time reverted from 4 to 3.
				Active time increased from 15 to 18.
			Hangars of 2 are removed.
			2 Large Energy mount angles increased from 165 to 180.
			Added 2 built-in Glints.
			Flux Capacity increased from 7500 to 8000.
			Acceleration increased from 65 to 80.
			Deceleration increased from 55 to 70.
			Maximum Turn Speed increased from 35 to 45.
			Mass increased from 1200 to 1700.
			Base Supply Maintenance/Repair cost increased from 25 to 32.
		Chimiria:
		Nadia:
			Designation changed from Combat Carrier to Battleship. (+ Mi)
			Acceleration reduced from 40 to 55.
			Base Supply Maintenance/Repair cost increased from 34 to 38.
			Mi:
				Acceleration reduced from 40 to 50.
				Base Supply Maintenance/Repair cost increased from 40 to 44.
		Utena:
			Added Integrated Oculian Optics hullmod.
			Titanic Phase Columns:
				Now reduce the Ordinance costs of Shiredains by 3.
				Now increases the Phase Stress limit from 50% to 60%.
				Now increases Kea base range for 150 units, while Pirouette series for 250 units.
				Shiredain Range bonus altered from 1.2x to flat base 200 units.
				Top Speed bonus increased from 40 to 50.
				Receives Integrated Target Unit buff and Delicate Machinery debuff, the preceeding hullmods are removed and blocked from use.
			All 16 Shiredain built-ins are now Small Energy slots.
			Base Supply Maintenance/Repair cost reduced from 58 to 48.
	Wings:
		Added the Loach wing (plus Mi), a support drone squadron that relies its survivability with its phase capability.
		Breeze:
			Hull increased from 60 to 100.
		Breeze Mikanate:
			Hull increased from 80 to 150.
			Flux Capacity increased from 100 to 150.
			Flux Dissipation increased from 25 to 35.
		Breeze Elite:
			Armor given from 1 to 40.
		Breeze Superelite:
			Armor given from 1 to 60.
		Cancer:
			Hull increased from 35 to 60.
			Flux Capacity increased from 75 to 100.
			Flux Dissipation increased from 25 to 40.
			Top Speed increased from 200 to 225.
			Acceleration increased from 215 to 300.
			Deceleration increased from 270 to 300.
		Cancer Elite:
			Hull increased from 40 to 120.
			Flux Capacity increased from 75 to 200.
			Flux Dissipation increased from 25 to 60.
		Cancer Mikanate:
			Base Ordinance cost reduced from 22 to 20.
			Weapons changed from 1 Glint, 2 Pixel torpedo to 2 Glints and 1 Kilopixel torpedo.
			Hull increased from 70 to 250.
			Flux Capacity increased from 75 to 300.
			Flux Dissipation increased from 25 to 90.
		Tick Elite:
			Hull increased from 250 to 350.
		Tick Mikanate:
			Hull increased from 300 to 400.
			Armor increased from 125 to 150.
		Cucumber:
			Hull increased from 1000 to 3000.
			Flux Capacity increased from 2000 to 4000.
	Weapons:
		Added Kilopixel Torpedo.
		Pirouette:
			Sound altered to have less bass.
			Flux per shot reduced from 45 to 25.
		Fouette:
			Flux per shot reduced from 45 to 30.
		Frappe:
			Flux per shot reduced from 40 to 35.
		Kea:
			Range reduced from 400 to 350.
			Damage per shot reduced from 50 (200) to 45 (180).
			Flux per shot reduced from 35 (140) to 30 (120).
		Blita:
			Energy Damage bonus against missiles increased from 50% to 100%.
			High Explosive Damage bonus against fighters increased from 50% to 75%.
			Fighter arc chance increased from 15% to 25%.
			Fighter arcs does half of the primary damage while double the displayed EMP damage.
			Damage per shot reduced from 70 to 60.
			Flux per shot reduced from 50 to 40.
			Charge down reduced from 0.25 to 0.1667.
		Gleam:
			Damage per second increased from 450 (142) to 500 (158).
		Prima:
			Range reduced from 750 to 650.
			Damage per shot reduced from 90 to 80.
			Flux per shot reduced from 60 to 50.
			Charge up time reduced from 0.25 to 0.15.
		Stredia:
			Range reduced from 750 to 650.
			Damage per shot increased from 100 to 140.
			Flux per shot increased from 80 to 105.
			First shot Damage increased from 300 (300% from 100) to 350 (250% from 140).
			First shot EMP damage increased from 30 to 100.
		Leia:
			Damage per shot increased from 70 to 75.
			Flux per shot reduced from 50 to 45.
		Manndie:
			Added the forgotten ocua_mikanate tag.
			Damage per shot increased from 120 (60x2) to 140 (70x2).
			Flux per shot increased from 80 to 90.
		Nicor:
			Range reduced from 850 to 750.
			Charge down time reduced from 1.9 (2.3) to 1.6 (2.0).
		Ruby:
			Range reduced from 1500 to 1200.
			Turn Rate reduced from 20 to 10.
			EMP per shot reduced from 100 to 90.
			Flux per shot reduced from 250 to 150.
			Charge down reduced from 1.2 to 1.
			Projectile Speed reduced from 3000 to 2400.
		Vira:
			Energy Damage bonus against missiles increased from 50% to 100%.
			High Explosive Damage bonus against fighters increased from 50% to 75%.
			Fighter arc chance increased from 15% to 25%.
			Fighter arcs does half of the primary damage while double the displayed EMP damage.
			Damage per shot reduced from 90 to 70.
			EMP per shot reduced from 45 to 35.
			Flux per shot reduced from 80 to 60.
			No longer has magazine size.
			Charge down reduced from 0.167 to 0.125.
		Flandrey:
			Damage per second reduced from 1250 to 1050.
			Flux per second reduced from 1250 to 945.
			Charge up time reduced from 2 to 1.5 seconds.
		Pixel++ Launcher:
			Charge down time reduced from 15 to 10.

**** Version 0.9.1a ****
	Meta:
		Ocutek Pirates are now a seperate download.
	Ships:
		Colision bound optimization. This helps reduce the lag significantly and allows a lot more Red spamming.
		Oculian Vapor Core:
			Logistics tag removed again. Since the Logistics limit somehow still applies.
	Wings:
		Cancer Pixel torpedo:
			Reduced base charge down from 10 to 1. You owe me.
			
**** Version 0.9.1 ****
	Ships:
		Important: Updated outdated descriptions.
		Oculian Hull hullmod:
			Supply cost reduction increased from 20% to 25%.
			Supply reduction now carries over to Recovery cost.
		Mikanate Overhaul hullmod:
			Has been completely overhauled:
				Was able to provide flat buffs towards ship stats and increase damage output.
				Now increases flux efficiency for weapons, provide Ordinance discounts with Mikanate weapons too.
				Additionally, it accepts 2 core configurations that merges into a specialized core mod.
				Comes with a Catalyst core that amplifies pure-strain core mods.
		(New) Mikanate Override hullmod:
			A makeshift hullmod that allows non-Mikanate ships to have 2 cores. Only sold in Oculian markets, not dropped.
		Overdriven Clock Systems:
			Priced added.
		Chemical Core hullmod:
			Flux Reduction bonus reduced from 20% to 15%.
			Recovery Cost penalty reduced from 100% to 67%.
		Crystalline Core hullmod:
			Zero Flux bonus multiplier added to compensate Maximum Speed loss.
			Note: The additional multiplier is still seen in the UI but the gameplay stats will say otherwise.
		Chimly:
			Mikanate variant added.
		Chimis:
			Mikanate variant added.
		Chimex:
			Mikanate variant added.
		Chimiria:
			Sprite and Loadout overhaul.
			Modular slot changes:
				From 3 Small Synergy, 6 Medium Energy, 1 built-in Kurtina and 6 built-in Glints,
				To 2 Large Synergy, 4 Small Synergy, 5 Medium Energy and 10 built-in Glints.
			Mass reduced from 2700 to 1800.
			Hangar Module:
				Additional 1 is added to the main hull and is moved to the sides, similar to Old Red Kuria.
				Loadout overhaul:
					Moved Large mount to the main hull.
					Now has 1 Medium Energy Turret and 2 built-in Glints.
		Gretly:
			Mikanate variant added.
		Prily:
			Mikanate variant added.
		Sophis:
			Mikanate variant added.
		Basilix:
			Mikanate variant added.
			Price increased from 32000 to 60000.
		Etna:
			Temporal Overclock:
				Charge Up time increased from 2.5 to 4.
				Active time increased from 12 to 15.
				Charge down time increased from 0.5 to 1.
		Nadia:
			Mikanate variant added.
			Sprite adjusted.
			Added 2 more built-in Glints.
		Utena:
			Fixed Titanic Phase Columns indiscriminately removes any buffs that tie to its current bonuses.
	Weapons:
		Added 1 new Mikanate weapon in the elite roster.
		Added Macroxel and Macroxel+, armored torpedo finishers.
		Ruby:
			Tier reduced from 3 to 2.
			Rarity removed.
		Voxel:
			Tier reduced from 1 to 0.
			Role changed from Strike to Support.
			Cooldown time reduced from 10 to 8.
	Wings:
		Mollusc (Mi):
			Resprited.
			Hull increased from 50 to 100.
			Flux Capacity increased from 225 to 300.
			Shield Arc reduced from 180 to 150.
			Shield Efficiency increased from 0.9 to 0.85.
		Breezes:
			Range increased from 3000 to 4000.
		Elite Breeze/Superelite Breeze:
			Range reduced from 3000 to 2000.
			Attack Run size reduced from 300/400 to 200.
		Kaleidos:
			Collision Bounds simplified.
			Added the missing Autonomous Drone hullmod.
			Mikanate variant added.
			Elite:
				Added the missing Elite Software hullmod.
		Ticks:
			Accelerated Energy Vents hullmod built-in added.
			Range reduced from 6000 to 2000.
			Added 1 Glint and 2 Pirouettes.
			Regular:
				Base OP cost reduced from 10 to 7.
				Wing size reduced from 3 to 2.
				Hull reduced from 200 to 150.
				Flux Capacity reduced from 500 to 200.
				Flux Dissipation reduced from 100 to 50.
			Elite:
				Accelerated Shields built-in added.
				Base OP cost reduced from 18 to 12.
				Wing sized reduced from 2 to 1.
			Mikanate:
				Base OP cost reduced from 25 to 22.
				Elite Software hullmod built-in added.
				Accelerated Shields built-in added.
				Wing size reduced from 2 to 1.
				Hull increased from 250 to 300.
				Flux Capacity increased from 500 to 600.
				Flux Dissipation increased from 120 to 150.