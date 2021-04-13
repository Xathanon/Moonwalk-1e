Movement:
=========
In a given Action Phase, a character has various amounts of movement, which they may use to move, depending on their mode of motion and their Agility.

Movement has two modes: a regular mode and a swift mode. Switching to swift mode is a free action that must be taken on one's action phase. One's speed in each movement type is determined by Agility times the movement multiplier for that type. If you switch to swift mode, you gain twice as much movement, but will be subject to Swift Movement modifiers. At the start of each Turn, you automatically return to regular mode until you use a free action to enter swift mode again.

The amount you have moved in a given Turn is taken out of all of your movement rates equally, and if you would be forced to use a movement type that you have no remaining movement in, you cannot move.

Sprinting:
----------
As a simple action, you can make a movement test. This is made with Strength + the appropriate movement skill (or Data Processing instead of Strength for Matrix Movement). Your hits are multiplied by the normal attribute, and that amount is added to your available movement for the Turn. You cannot take this action if the only movement type you may use is Crawling.

At the end of an Action Phase in which you sprint at least once, you must resist an amount of stun damage equal to the number of consecutive Action PHases in which you have used Sprint, using Fortitude + Willpower instead of Fortitude + Armor.

Swift Movement:
---------------
Swift Movement incurs the following effects:

* -2 penalty to all ranged attacks made against the character.
* -2 penalty to all actions taken by the character.
* Other instances recorded as regards the specific actions or options affected by them.

+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
| Standard Movement Multipliers   | Multiplier   | Standard movement multipliers can be used by any entity without the {Missing Movement Type} trait.                |
+=================================+==============+===================================================================================================================+
| Walking                         | 3            | Walking is the standard movement type, used for most travel overland. Swift movement of walking is running.       |
+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
| Swimming                        | 1            | Swimming is exclusively used for moving whilst submerged or at least floating on water or another liquid.         |
+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
| Crawling                        | 1            | Crawling is only required when prone, and is the only movement type that can be used whilst prone.                |
+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+

+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
| Unusual Movement Multipliers    | Multiplier   | Unusual movement multipliers can be used only by entities that have gained access to them by powers or traits.    |
+=================================+==============+===================================================================================================================+
| Flying                          | 5            | Flying is exclusively self-powered flight, not including gliding or falling.                                      |
+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
| Climbing                        | 1            | Climbing movement is exclusively for entities that can climb in unusual circumstances, such as spiders or geckos. |
+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+

+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
| Otherworld Movement Multipliers | Multiplier   | Otherworld movement multipliers are only used in their respective worlds, never in the physical world directly.   |
+=================================+==============+===================================================================================================================+
| Astral Movement                 | 10           | Astral movement is used for creatures with the [Astral Essence] trait, and is applied to Intuition, not Agility.  |
+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
| Matrix Movement                 | 10           | Matrix movement is used for personas in the matrix only, and is applied to Data Processing instead of Agility.    |
+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+

Lifting and Carrying:
=====================
The amount of weight a character can manipulate is equal to their Strength times a factor based on what they wish to do with the object: 

* 10 to carry normally and manipulate
* 20 to lift with encumbrance
* 30 to drag. 

A character may use a complex action to make a lifting test; this is a Strength + Fortitude test. One's strength is multiplied by the hits on this test for a particular lifting. Measurements are in kilograms.

Inherent Limits:
================
Any Test that includes a skill in its calculation and does not state another limit uses one of the three inherent limits. See the table below for specifics and calculations:

+-----------------------------------------------------------------------------+---------------------------------------------+
| Inherent Limit | Calculation                                                | Used For Skill Categories                   |
+-----------------------------------------------------------------------------+---------------------------------------------+
| Astral         | ((Potency or Somatesthesia * 2) + Willpower + Intuition)/3 | Magical                                     |
+-----------------------------------------------------------------------------+---------------------------------------------+
| Mental         | ((Logic * 2) + Intuition + Willpower)/3                    | Crafting, Matrix, Technical, Pseudo-Magical |
+-----------------------------------------------------------------------------+---------------------------------------------+
| Physical       | ((Strength * 2) + Agility + Fortitude)/3                   | Somatic, Weapon, Vehicle                    |
+-----------------------------------------------------------------------------+---------------------------------------------+
| Social         | ((Charisma * 2) + Intuition + Willpower)/3                 | Social, Pseudo-Social                       |
+-----------------------------------------------------------------------------+---------------------------------------------+