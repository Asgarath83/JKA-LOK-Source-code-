# JKA-LOK-Source-code-

Project is written in C/C++. Compiled with Visual Studio 2010 
WIP source code related a mod conversion of JKA about LOK series 

This is a work in progress, so is not again finished. 
It's the source code of a mod for Jedi Knight Jedi Academy Single Player about Legacy of Kain. 
Code can be used as example for making some kind of RPG fantasy mod with JKA engine. 
There is a system of custom effects and sounds for each ai CLASS that cast shoots or force powers. 

Changed: 
- force fall: Npc and player with fall by jumps with floating and consuming force power, if they press jump key on air. like Kain jumps into blood omen 2. 

WEAPONS 
- Weapons models of the mod are removed for many of star wars weapons, replaced with a simply tag model for shoot magic by hands of characters.
weapon list: 
SABER: swords and reavers. added a new command "reavercharge" for file SAB, if is setted on 1, Katamove 
emit splashdamage knockback and hitotherefx at 50 of force point costs 
WP_BLASTER_PISTOL: darkness projectiles. same class can shoot smoke and void projectiles with increased damaged. 
WP_BLASTER: fire, warm and magma projectiles.
WP_DISRUPTOR: a yellow ray of light, deadly on undeads. 
WP_DEMP2: spirit \ ghost projectiles, deadly for undeads, hylden and demons. 
WP_BOWCASTER: light projectiles, same classes shoot sun and lightning projectiles with electrocuted effect and damage increased. 
deadly on vampires. 
REPEATER: frost, water projectiles. big damage on vampires. 
FLECHETTE: earth weapons. the shoots are deadly for winged and flying creatures. 
ROCKET LAUNCHER: air weapons. deadly for golem and earth creatures. 
THERMAL: poison\elemental grenades. 
TRIPMINE: sonic mine
DETPACK: quake bombs. 
POISON: new weapon, it's a single player version of noghri stick. 
JAWA: available for single player, use sonic projectiles. 
BLOODGUN: new weapons, a gun deadly for vampires.
CANNON: new weapons, an alchemic flechette cannon deadly for vampires. 
TUSKEN RIFLE: a bowcaster with elemental arrows. 
BRYAR_PISTOL: a bow with elemental arrows. 

FORCE POWERS: HACKED for make the vampiric spells. many classes can cast their own version of these powers. 
HEAL: vampiric regeneration, devouring of souls, holy heal for humans. 
PROTECT: repel shield of blood omen. 
ABSORB: magic repel shield of blood omen. 
MINDTRICK: an arcane power , with mindtrickscript will affected enemies with elemental status like poisoned, webbed, electrocuted, burned, blinded, etc. 
LIGHTNING: each class now shoot an elemental variant of force lightning. 
DRAIN: blood gout, blood shower, necromantic and soul drain. 
RAGE: fury for vampires, magic shield for humans and other creatures. 
GRIP: telekinesis aka TK'of Kain and Turel into defiance game. 
PUSH: force cinetic shoot. 
PULL: telekinesis pull. 
JUMP: vampiric levitation. 
SABER_DEFENSE: deactivated the projectiles deflection is possible to parry magical shoots with saber and shiedl,
but not deflect to casters. 
SABER_OFFENSE. not edited.
SABER_THROW: not edited. 
NEW FORCE POWERS: 
STUN: act like mindtrick level1-2, stunning enemies. 
HATE: enemies pass to playerteam and fight each others. cast again for turn it to team enemy.
wrack: you can control an enemies. it fight for player. 
controlmind: you can control enemies. 
FEAR: shooter enemy drop weapons, surrender and flee. 
FREEZE (WIP) enemy are stucked into a place, no saber defense, no moving. 

OTHERS THINGS: 
added in g_combat a system related strenght and weakness to elemental weapons. every CLASS is aligned a one kind of creature and is resistance to certain weapons, and weak to thers. 
-Expand max force power and max weapons to 32. 
-Expand buffer for visual effect (WIP again) for allow to engine to support and show more EFX as possible without hiddind and mask.














