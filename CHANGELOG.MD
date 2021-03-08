# Changelog
- Notable changes from the original version of this mode

## [1.7.2] 3/08/2021
### Added
- **General** Added a host only server load hud
### Changed
- **General** Changed several HUD items to be gender non specific and other general updates
- **Brig**: Damage increased to 275%
- **Brig**: Healing Received increased to 275%
- **Junkrat**: Added increased passive damage while ulting and changed HUDs for that too Small Messages
- **Lucio**:  Healing Received increased to 20%
- **Lucio**: Changed the wait condition in ult to try and prevent double firing
- **McCree**:Ult generation increased to 350%
- **Moira**: Healing Dealt/Received increased to 60%
- **Moira**: Fade's cooldown changes based on power level. <500  =1  seconds,>=500  && <=1000 = 1 seconds,>1000  && <2000 = 6 Seconds,>2000 = 30 seconds. Health restrictions removed
- **Reaper**: Ammo clip size increased to 300%
- **Torb**: Ammo clip size increased to 300%
- **Zenyata**: Added a teleport death spot for Hollywood
- **Zarya**: Abort code added to try and prevent ult from breaking game.

## [1.7.1] 3/06/2021
### Changed
- **Lucio**: Ult range decreased to 10% and HUD wording updated
- **Lucio**: Spawns with Ult
- **Mei**: Damage increased to 150%
- **Mercy**: Starting ult charge now 55%
- **McCree**: Flashbang cooldown reduced to 30%
- **Winston**: Ult duration increased to 300%
- **Zarya**: Black Hole Effect Added with Ult
- **Zarya**: Briefly unkillable during ult to try and prevent the game bugging out
- **Zenyata**: Ammo reduced to 2


## [1.7.0] 3/02/2021
### Added
- **General**: QP/Comp HUDS no longer block the in game huds :D

### Changed
- **General**: Ashe,Lucio,Mercy,Sigma,Torb,and Zarya spawn with 65% ult charge plus general ult gain tweaks
- **General**: Low health heroes armor increased to 50 armor each kill non healable (Ashe,Widow,Pharah,Reaper,Genji)
- **General**: HUD improvements and rewording for Ashe,Wrecking Ball,Winston,Widow,Sym,Zenyata,Moira,Orisa
- **General**: Reenabled Hollywood and Kings Row 
- **General**: Roadhog and Orisa global level 2  counter corrected
- **Ana**: Sleep ability reenable during Level 2
- **Brig**: Shield cooldown reduced to 80%
- **Junkrat**: Burn damage from passive increased from 10 dps to 20 dps
- **Lucio**: New Ultimate:Players near where Lucio lands with his ult drop through the ground. This should allow for more kills when on maps without boop places
- **Lucio**: Damage increased when wall riding 
- **Lucio**: Shield gain per Env kill decreased to 30%
- **Moira**: Fade's cooldown changes based on power level. <500  =  seconds,>=500  && <=1000 = 6 seconds,>1000  && <2000 = 15 Seconds,>2000 = 90 seconds
- **Reaper**: Health reduced to 35%
- **Reinhardt**: Shatter damage increased from 30 to 
- **Tracer**: Rewind abilitiy no longer disabled on spawn. This was originally a bug fix but it sometimes causes issues if they die before its turn back on
- **Tracer**: Prevent double speed force
- **Zarya**: Improved ult clean up code to help avoid players getting stuck. 

## [1.6.1] 2/26/2021
### Added
- **General**: Ashe,Mercy,Sigma,Torb, and Zarya spawn with 45% ult charge
### Changed
- **Lucio**: Re-enabled crossfade. Reduced healing. Also increase primary fire damage slightly. Would love for Lucio to stay around longer so playing with things
- **Moira**: Fade's cooldown changes based on power level. <500  = 3 seconds,>=500  && <=1000 = 15 seconds,>1000  && <2000 = 45 Seconds,>2000 = 90 seconds

- **Tracer**: 1)Fixed issue where her health pack's didn't reset at death. 2)Reduced health pack gain from 25% to 15% to reduce the speed at people triggering speed force
3)Fixed an issue where people were stuck in speed force if tracer leaves game while in speed force.


## [1.6.0] 2/20/2021
### Added
- **General**: Low health heroes get 20 armor each kill (Ashe,Widow,Pharah,Reaper,Genji)
- **General**: Support for Kanezaka

### Changed
- **General**: Changed Paris lava positioning
- **Hanzo**: Reenabled Sonic Arrow
- **Lucio**: Each time a hero is booped off the map. Lucio gets 50% of that character's health in shields
- **Moira**: Reenabled fade at a cooldown of 60s
- **Wrecking Ball**: Reworked ultimate so that he auto ults 5 times while invisible. Spawns with it.
- **Zarya**: 1)Gains 3000 armor while ulting 2)Added a note warning player not to ult while another Zarya is ulting 3) Increased pull speed

## [1.5.2]
### Changed
- **Junkrat**: Reduced the distance checking rate of the Auto dot to reduce server load

### Removed
- **Moira**: Removed ball spam. It crashed the server a lot

## [1.5.1]
### Added
- **General**: Health packs now heal by as a percentage of max health except for tracer

### Changed
- **Ashe**:Bob nerfed to 200%
- **Lucio**: Fixed an issue with people getting stuck in the air because of Lucio's ult
- **Moira**: Auto spams balls
- **Reinhardt**: 1)Self Damage from ult Fixed. 2)Targets of the the ult are no longer damaged multiple times
- **Torb**: Fixed armor stacking bug
- **Widow**: Spawns with ult now and sights time reduced significantly. Her silhouette is now visible  


## [1.5.0]
### Added
- **Ashe**: Now goes invisible while B.O.B. is alive
- **Junkrat**: 1)Added burning effect 2)Burning dot is now applied when players are close to him 3)Immune while ulting 4)Decreased cooldown of concussion mine
- **Widow**: Widow can now shoot through walls while ulting

### Changed
- **Torb**: Torb gains armor while ulting to be able to make it long enough to get in the armor for protection
### Removed
- **Doom**: Autofisting


## [1.4.1]
### Changed
- **Reaper**: Fixed bug with players automatically falling through the map while wraithing
- **Sigma**: Fixed bug when two sigmas ult back to back/ one leaves tghe game

### Removed
- **Reinhardt**: Removed vacuum charge as it was very buggy. Will Revisit

## [1.4.0]
### Added
- **Sigma**: Sigma's ult now does fall damage 
- **Reaper**: Reaper can now wraith through walls
- **Reinhardt**: Added AOE Earthshatter. Charge "vacuum"

### Changed
- **Ana**: Ana is now invincible while ulting
- **Ashe**: Added unlimited ammo and more decreased cooldowns due to player feedback. "Ashe is trash"
- **Doom**: Added auto targeting for his fist
- **Roadhog**: Reduced hook cooldown 
- **Sombra**: All damage hacks for 1 second

## [1.3.1]
### Changed
- **Ana**: Fixed bug where players retained ability to sleep with any damage between characters
- **Torb**: Fixed bugs related to players leaving during the ult
- **Tracer**: Reworked speed force to not rely on health but track health pack accumulation.

## [1.3.0]
### Added
- **Torb**: Introduced the concept of the Lava God. Players become the Lava God allowing them not to be burned by the lava.

### Changed
- **Ana**: Reworked Ana's level 2 so that it now makes her shoot darts that sleep for exactly 5 seconds and then kill her target. Targets are guaranteed kills
- **Zarya**: Changed ult to make sure Zarya is 100% charged while doing it. Reduced Cooldown on bubble

## [1.2.1] 
### Added
- Increased Bastion,Sigma and Zarya's Speed
- Environmental kills caused by Zen,Lucio,Sigma,Torb's new abilities now currently count as kills


## [1.2.0]
The original version. This repo was "forked" from it https://workshop.codes/REEH3 
```

