Injury and Healing
==================
This is what happens when you get shot, hit with a data spike, or hit by a car. The world of Moonwalk is not safe, and you might be coming back here quite often to try and get patched up.

Condition Monitors:
===================
Condition monitors are how damage to things is measured. A condition monitor has a number of boxes as per its unique calculation based on what kind of condition monitor it is. When damage of a certain type is dealt to any entity, if any damage remains after the resistance test (or if the damage is unresisted, all of it) fills one box per unresisted damage. There are five different types of condition monitors, each with their own rules for recovery and what happens when they are filled. A given condition monitor's test listed below to remove boxes from it is known as its recovery roll - for example, a stun recovery roll is the test that removes boxes from the stun condition monitor.

Physical Condition Monitor:
---------------------------
* All physical things have a physical condition monitor, including objects and buildings. A physical condition monitor for a living being has boxes equal to 6 + (Fortitude/2). If a physical condition monitor is completely filled for a living creature, the creature becomes bleeding out (see conditions) but not necessarily unconscious, and any additional damage goes to the overflow condition monitor at a one-to-one rate. If the physical condition monitor of an object or building is completely filled, it is destroyed.
* Objects calculate their physical condition monitor with boxes equal to their Structure rating. Buildings calculate their physical condition monitor as the sum of all the physical condition monitors of all their constituent parts (normally walls).
* Filled boxes on a living being's physical condition monitor are naturally emptied by a physical recovery roll, a Fortitude + Fortitude extended test with an interval of one day. Boxes equal to the hits on each test are emptied.
* Filled boxes on an object or building's physical condition monitor are emptied by a living being making a test using Logic + the appropriate engineering skill [Mental] extended test with an interval of one day, and each hit removes one box from the object's physical condition monitor, assuming appropriate tools and materials (see Repairing Objects)
* Damage dealt to the physical condition monitor is written as XP or as any amount of physical damage.

Stun Condition Monitor:
-----------------------
* All living things have a stun condition monitor. A stun condition monitor has boxes equal to 6 + (Willpower/2). If a living creature's stun condition monitor is completely filled, they are rendered unconscious, and any additional damage to it goes to the physical condition monitor at a two-to-one rate.
* Filled boxes on a stun condition monitor are emptied with a stun recovery roll, which is a Fortitude + Willpower extended test with an interval of one hour. Boxes equal to the hits on each test are emptied.
* Damage that fills stun condition monitor boxes is written as XS or any amount of stun damage.

Overflow Condition Monitor:
---------------------------
* Living things that have a physical condition monitor (that's almost all of them) have an overflow condition monitor. An overflow condition monitor has a number of boxes equal to the creature's Fortitude stat. If all boxes in a creature's overflow condition monitor are filled, it is dead.
* Filled boxes on a living being's overflow condition monitor can be removed only by the use of magic or medicine: see 'healing' for details.

Matrix Condition Monitor:
-------------------------
* All devices have a matrix condition monitor. A matrix condition monitor has boxes equal to 6 + (Device Rating/2). A device, even a persona running on a device, takes no wound penalties - but if a device's matrix condition monitor is filled, it may not be used again for any purpose (even non-wireless ones) until all of its boxes have been emptied.
* Filled boxes on a matrix condition monitor are emptied with a Hardware + Logic [Mental] (number of filled boxes, one hour) extended test.
* Damage that goes to the matrix condition monitor is written as XM or any amount of matrix damage.

Core Condition Monitor:
-----------------------
* A core condition monitor is exclusive to AI, and has boxes equal to 6 + (Depth/2). When an AI's Core Condition Monitor is filled, its code has become so corrupted that it can no longer function - it is effectively dead.
* Filled boxes on a Core Condition Monitor can be removed during realignment, by making a core recovery roll. The AI makes a Computer + Depth [Essence] test each time it realigns, emptying boxes equal to its hits.

Healing:
========
Sometimes just waiting to recover naturally isn't good enough. Thankfully, medicine has grown beyond the Dark Ages, so there's a good chance you can get healed without just waiting for your body to do it naturally.

First Aid:
----------
* With all the fancy tech in the world, first aid is still relatively simple. The treating character makes a First Aid + Logic [Mental] test. At least two hits will stabilize a living being that is bleeding out. Each hit beyond the first empties one box from your choice of physical, stun, or overflow condition monitor.
* A character that has been treated with First Aid cannot be treated with First Aid again until they have taken damage again, and subsequent uses of First Aid cannot empty boxes that the original test failed to empty. (For example, someone takes four physical damage, is treated and two boxes are emptied, then takes another two damage. Even if enough hits are rolled to remove more than two boxes, the subsequent attempts cannot remove those boxes.)

Magical Healing:
----------------
* Magical healing takes the form of a variety of health spells, the particulars of which will be handled in their entries. Nonetheless, it is important to note that after magical healing is applied to a particular condition monitor, that condition monitor cannot be affected by First Aid unless further damage is taken, as if it had already been treated with first aid. It is well-advised to apply first aid, followed by magical healing if available, in the field, followed by longterm care after the injury.

Assisted Recovery:
------------------
* Over extended periods of time, the body can heal itself. But proper treatment can make that a helluva lot easier. At the start of the a physical or stun recovery roll, a character can make a Logic + Medicine [Mental] test. Each hit on this test grants a +1 modifier to the subsequent recovery test.
* Making an Assisted Recovery test takes one minute for a stun recovery test, and one hour for a physical recovery test.

Wounds:
=======
Wounds aren't just numbers and boxes on your condition monitors, like some kind of health  bar. Being injured has an effect on your capabilities, most of the time.

Wound Modifiers:
----------------
* Wound modifiers are incurred for every third box that is filled on the Stun or Physical condition monitor of a living being. Each time a wound modifier is incurred, it inflicts a -1 penalty to all tests the being makes that are not tests made to resist or recover from damage (the penalty still applies to tests made to heal or treat yourself or others, just not natural recovery).
* Wound modifiers persist until the next time the creature can make a recovery test for the appropriate condition monitor, even if the boxes that inflicted the wound modifier are healed. (Example: Take three physical boxes, gain a -1 wound modifier. Get healed for two boxes by a Heal spell. Take another two physical boxes, gain another -1 wound modifier on top of the first -1. Rest overnight and even if you don't recover more than one box, both penalties are gone... for now.)
