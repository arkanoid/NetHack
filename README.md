# Nethack Bard and Music patch

**Note: this is currently a work in progress, code won't compile for now.**

## Concept

Musical instruments (the normal, non-magic ones) in Nethack have some minor effects. For example: playing a wooden flute have a chance to pacifying snakes based on dexterity and experience.

The idea is adding a new class, the Bard, which can use those instruments with much stronger effects, being almost a kind of magic. This class takes some inspiration from the Bard class from other RPG games (like D&D) and the greek myth of Orpheus.

This patch adds a new skill, Music. Classes with no experience in this skill will play the existing instruments the same way they already work in vanilla Nethack. Classes with experience in Music can play the same instruments with stronger effects, affecting all monsters around. Bards are the only class that can advance the Music skill up to expert.

The previous Bard patch (0.9) used a different system where musical instruments were used to 'cast' enchantment spells in music form. This new version aims to simplifies things while still delivering a Bard archetype that can work within vanilla Nethack concepts.

## Musical instruments effects
### In vanilla
How normal, non-magic musical instruments work in vanilla:
- tooled horn: awaken and possibly scare nearby monsters.
- wooden flute: chance to pacify nearby snakes, based on dexterity and experience.
- wooden harp: chance to pacify nearby nymphs, based on dexterity and experience.
- bugle: awaken, anger, and unparalyze all soldiers and watchmen on the level. Can also awaken or scare other nearby monsters (like a tooled horn).
- leather drum: awaken and scare nearby monsters (including pets).

### In Bard and Music patch
This is a basic description of the effects. For the full effects, check the SPOILER section at the end.
All chances are based mainly on charisma, with some dexterity and experience being also used.
- tooled horn: chance to scare or confuse nearby monsters.
- wooden flute: chance to make nearby monsters sleep, or temporarily tame.
- wooden harp: chance to temporarily tame monsters, or sleep.
- bugle: increases chance pets will attack, and chance to increase their damage.
- leather drum: increases pets' damage, smaller chance to scare monsters.
