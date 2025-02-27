# Rocket Sound Enhancement
Rocket Sound Enhancement (RSE) is an Audio Plugin Framework Mod for [Kerbal Space Program](https://www.kerbalspaceprogram.com/) that offers modders advance sound effects features not available in the base game. 
It features a robust Layering System for use of multiple sounds just like in other games (eg: FMod). 

By itself, RSE only does Sound Limiting and Muffling. You'll need to download a Config Pack Mod in order to have new sounds in your game.
If you release a mod that uses RSE, let me know so I can add it here in a list!

Get the Default Config here:
[Rocket Sound Enhancement Default](https://github.com/ensou04/RocketSoundEnhancementDefault)


## Features
### Audio Muffler
- Normal: Mixer based Audio Muffler with Dedicated channels for Exterior Sounds, Focused Vessel and Interior. With Doppler Effect.
- AirSim: Works on top of Full Quality, Parts with RSE Modules will simulate realistic sound attenuation over distance, comb-filtering, mach effects, sonic booms (via ShipEffects) and distortion. Stock sound sources has basic mach and distance attenuation (volume or filter based) support.

### Master Audio Limiter/Compressor
Sound Mastering that controls the overall loudness of the game with Adjustable Amount for different dynamics.

### Part Modules
Apply sounds with Layering Capabilities with these part modules. 
For eg: Using a different Loop sample for low thrust compared to High Thrust on a single Engine.
- RSE_Engines
- RSE_RCS
- RSE_Wheels
- RSE_RotorEngines

Replace and/or Add Sounds to Decouplers, Launch Clamps and Docking Ports.
- RSE_Coupler

EFFECTS Nodes - A Simpler non-layer version of RSE Modules for drop-in replacement of Stock AUDIO{} with full AirSim Support and a more direct Muffling Support.
- RSE_AUDIO
- RSE_AUDIO_LOOP

### ShipEffects & ShipEffectsCollisions 
**Physics based Sound Effects System**
- Add sounds and assign it's Pitch or Volume to any physics variable available for each Vessel
- Add Collision Sound Effects for different surfaces to any Part
- Replace or Disable Staging Sound Effects
