v2.10.0
=====
- Removed dependency on Celestial Body Science Multiplier Editor
- Added dependency on Kopernicus
- Added missing FOR passes to PBC patches

v2.9.3
=====
- Added support for 38 new parts from StationPartsExtendedRedux (thanks for the heads up @Cholerix)
- Updated Core Chart with SPER image

v2.9.2
=====
- Increased EVA Suit mass carry limit from .1 to .105 (weather unit)
- Updated Kerbalism patch with 11 new parts, Prosemian containers (thanks @kitamoboz)

v2.9.1
=====
- Antenna Range Rework, adjusting recommended DSN modifier from 80% to 35%
    - Increased low-end Relay from 5M to 20M
    - Increased mid-range Direct from 20G to 25G
    - Increased mid-range Relay from 15G to 20G
    - Increased high-end Relay from 75G to 100G
- Updated Core and Deprecated to include Version-2 HG-5 Antenna (low-end Relay)
- Updated Core to include Stock Magnetometer science part
    - If DMagic is present, the Stock Magnetometer is removed from the game (2 identical parts with separate science tracking is no good)
- Increased SAS Service Level by 1 for - Vanilla QBE Probe Core, RLA_Reborn "TET" Probe Core, USI Mk1 Wedge Probe Core
- Updated USI to include USI Mk2 Wedge Probe Core
- Increased Kerbal volume and mass carry limits so carrying an EVA Suit and ANY ground experiment at the same time is now possible. Coming up just short was so obnoxious...

v2.9.0
=====
- Updated for KSP 1.12+
- MiniAVC folder removed from download package, version file updated
- Removed patch that was resurrecting deprecated ScanSAT parts
- Updated new ScanSAT part placements

v2.8.0
=====
- Updated for KSP 1.8.0/1.8.1
- Added Breaking Ground Expansion support.
- Added KSP v1.8 Bonus-Parts support.
- Added new custom part - R061 Turboshaft Engine; a 0.6m LF Prop Engine for early aviation.
- Added newly reskinned vanilla parts to existing patches, moved deprecated variants to existing anti-exploit patch.
- Sorted new Universal Storage 2 Probe Core.
- Corrected xmit values for all Universal Storage 2 science wedges.
- Corrected Missing History [EnginePlate1] cost.
- Adjusted Breaking Ground deployable science yields to match the rest of PBC. (reduced to 70% of vanilla yields).
- Dropped tech unlock node position for mid-game and higher antenna by ONE(1) (RA-2, HG-55, RA-15, Comm 88-88, RA-100).
- Repackaged ScienceParamModifier mod in PBC download (it was never meant to be removed, whoops!)

v2.7.0
=====
- Updated for KSP 1.7.0.
- Added Planetary Base Systems mod support.
- Added additional preemptive support for Kerbalism 3.0.0.
    - Choosing to enable Kerbalism's 'Feature Science' will automatically override PBC's science reward values.
    - Choosing to disable Kerbalism's 'Feature Science' will automatically reinstate PBC's science reward values.
- Reduced research cost of SPER 18-man inflatable hab.
- Sorted new vanilla 3.7m and 5m Nosecones.

v2.6.0
=====
- Added USI - Life Support mod support
- Added support for 6 new KIS parts.
- When SPER and USI-LS are both installed, the Visual Observation experiment will be available on the USI cupolas.
- Added reminder note in probe contracts to tag your vessel as a PROBE, vs RELAY, ROVER, DEBRIS, etc.
- Fixed Dres Contract sort order.
- Corrected DMagic - Small SIGINT antenna range from 1Tril to 50bil.
- Shifted DMagic - Small SIGINT 3 nodes later.
- Corrected DMagic - Large SIGINT antenna range from 10Tril to 500Bil.
- Shifted DMagic - Large SIGINT 2 node later.
- Shifted TACLS 2.5m Storage parts one node later.
- Shifted TACLS 2.5m Recycler parts two nodes later.
- Shifted TACLS 3.7m Storage parts one node later.
- Shifted TACLS 3.7m Recycler parts one node later.
- Shifted SPER 2.5m Greenhouse two nodes later.
- Shifted SPER 3.7m Storage parts one node earlier.
- Shifted SPER 3.7m Greenhouse & Aqua one node later.
- Shifted Kerbalism 2.5m Greenhouse two nodes later.
- Shifted Kerbalism 2.5m Storage parts one node later.
- Shifted Kerbalism 3.7m Storage parts one node later.

v2.5.1
=====
- Small hotfix to ensure CKAN users receive the correct celestial multipliers.

v2.5.0
=====
- Integrated Science Param Modifier by DMagic; Celestial Multipliers Overhauled.
- Added B9 Aerospace Core Pack Support.
- Added RLA Reborn Support.
- Pre-KSP_v1.6 parts now mirror their updated post-KSP_v1.6 variants. Thank you @4x4cheesecake!
    - (Note this just prevents potential exploits. KSP versions prior to 1.6 are still not supported)
- Corrected lack of entry cost for Mk1 parachute and Modular Girder.
- Corrected antenna range of DMagic Soil Moisture from 100bil to 3.5bil
- Corrected antenna range of US2 variant of DMagic Soil Moisture from 50bil to 5bil
- Corrected NF-Spacecraft engine costs.
- Shifted DMagic MiniGoo and MiniLab laterally from Construction branch to SpecializedScienceTech.
- Shifted NearFuture 0.6m Structural parts laterally to PrecisionEngineering.
- Shifted vanilla Place-anywhere 1-port RCS block one node earlier.
- Shifted NF-Spacecraft RX-1 Linear RCS block one node earlier.
- Updated Readme.

v2.4.0.0
=====
- Added MkIV Spaceplane Support.
- Added KAS Support.
- Added KIS Support.
- CKAN updated to include more details and current information.
- Corrected autoAccept to false on Kerbol Contracts.
- Corrected placement of 2.5m Service Module.
- Corrected placement of Krane and Station Arm.
- Corrected overpriced NF-Aero part in High Altitude node.
- Removed 2 instances of :NEEDS[Squad Expansion] tag that didn't belong in the main cfg.
- Removed unintentional Dmagic-US1 part placements. US1 is not supported.
- Shifted several vanilla Mk3 Spaceplane parts into more consistent nodes.
    - Generally speaking, short and medium parts are unlocked with the Mk3 Cockpit, and the large/long parts arrive one node later.
- Shifted vanilla Large Radial Decoupler one node later.
- Shifted Gravimeter one node later.

v2.3.0
=====
- Added Kerbalism Support
- Added Probe Control Room Support
- Moved Science Definitions to a separate file named Zs_Science.cfg.
    - Deleting this file will return Science values to vanilla settings and will allow other mods Science Defs to take precedence.
- Removed autoAccept feature from all contracts.
    - Causing more problems than its worth, I'll bring it back when the bug is fixed.

v2.2.0
=====
- Added Near Future Support (all 7 modules; 257 parts reviewed)
- Added RealChute Support
- Added KAS Support (no cfg needed)
- Added KIS Support (no cfg needed)
- Added miniAVC.
- Corrected typo preventing Atmospheric Analysis part from appearing in tech tree.
- Shifted 0.6m vanilla RCS tank to flight control branch, one node earlier.
- Shifted 1.8m and 2.5m vanilla RCS tanks one and two nodes later, respectively.
- Shifted short-size 2.5m LFO fuel tank to same node as first 2.5m engine unlocks.
- Shifted mid-size 2.5m LFO fuel tanks one node later.

v2.1.0
=====
- Improved Contract Vessel Tracking.
- Removed option to cancel contracts. No longer needed.
- Small increases to select contract payouts.
- Reworked parameter rewards to increase difference between each step.
    - ie, "Fly By" pays less and "Return" pays more
- Corrected lack of SPLASHED condition check for Eve and Laythe.
- Gave Dres Contracts. Whoops
- Corrected parameter message for Crewed Ike contract.

v2.0.3
=====
- Created new "Tiny Basic Fin" part intended for 0.6m profiles. Available at Start.
- Shifted 0.6m Nose Cone two nodes earlier.
- Shifted FL-A5 (Nearly flat 0.6 > 1.2) Adapter three nodes earlier.
- Added basic Kopernicus support.
    - Contracts are still only built for stock planets, but they will work as intended in your Kopernicus install now.
- Corrected bug that prevented Eeloo contract from working correctly.

v2.0.2
=====
- 25% increase to mini-milestone funding rewards.
- 100% increase to Layer 1 science rewards.
- ~250% increase to Layer 1 funding rewards.
- ~25% increase to Layer 2 funding rewards.

v2.0.1
=====
- Increased funding-rewards for Layer 1 and Layer 2 contracts (hit em with the nerf hammer too hard)
- Small typo fix in Layer 3 Contract config

v2.0.0
=====
- Added Original PBC Contract Pack
- Shifted kOS 0.6m to Start Node
- Shifted kOS 1.2m one node earlier
- Shifted kOS Basic Radial one node earlier
- Updated kOS map
- Updated Missing History map
- No changes needed for KSP 1.6.1

v1.7.0
=====
- Added RemoteTech Support

v1.6.0
=====
- Added Missing History Support First pass on vanilla and MH fuel tanks.
- First pass on vanilla and MH engines.
- Shifted Mk2 lander one node later.
- Shifted Mk1-3 CM one node earlier.
- Shifted Mk2 CM one node earlier.
- Shifted 1.2m Reaction Wheel one node earlier.
- Shifted 1.2m Nose cones one node earlier.
- Shifted Z1k battery one node earlier.
- Corrected Entry and VAB costs for a few SPER parts.

v1.5.0
=====
- Added StationPartsExpansionRedux Support
- Telemetry Report experiment is now present on all Probes.
- First pass on all vanilla structural parts, and a few misc parts.
- Corrected placement of MH 1.8m HS.
- Corrected placement of vanilla 2.5m Hitchhiker module.
- Shifted placement of vanilla 2.5m Docking Port one node earlier.

v1.4.0
=====
- Added kOS Support.
- Added TAC-LS Support.
- Added SCANsat Support.
- Moved vanilla cupola one node later.
- Corrected entry and part costs for vanilla CMs.
- Corrected entry and part cost for RC-LO1 (largest probe core).

v1.3.0
=====
- Added Universal Storage 2 support
- General rule of thumb is if the US2 part is some improved version of an already existing part, it appears one node later than that original part.
- US2 Part costs were also heavily rebalanced, they were frequently way too cheap.
- First pass on vanilla ladders.
- First pass on vanilla decouplers.
- First pass on Making History decouplers and engine plates.
- First pass on vanilla docking ports.
- First pass on Making History docking port.
- Submitted mod for inclusion on CKAN.

v1.2.1
=====
- Added Making History support
- When Making History is detected, the CM placements are shuffled slightly so things stay nice and granular.
- Mk1 Lander shifted one node earlier.
- Mk2 Lander shifted one node later.
- Mk1-3 shifted one node later.
- Corrected placement of Rover Body part. Forgot to reference the new _v2 variant.
- Reordered Service Modules.
- Switched direct and relay ranges. Direct variants are unlocked before their Relay counterpart and have a longer range,
- but are incapable of relaying signals . Now you really have choices to make.

v1.1.0
=====
- Added DMagic Orbital Science support
- Added more verbose tags for MM, should prevent compatibility issues.
- Added SAS to Stayputnik so the first 5 minutes aren't so difficult.
- Corrected Atmospheric Sensor not appearing in the tech tree.

v1.0.0
=====
- First Version