Core Tables
===========
For convenience's sake, tables for the Core rules are consolidated on this page.

=============== ========================================== ==========================
Barrier Type    Totalled                                   Affected
=============== ========================================== ==========================
Wall            Olfactory, Tactile, Taste, Thermal, Astral Sonar/Ultrasound, Auditory
Sonic Generator Sonar/Ultrasound                           Auditory
White Noise     Auditory                                   Sonar/Ultrasound
Mana Barrier    Astral                                     N/A
=============== ========================================== ==========================

================ ========================
Sense            Applicable Modifier     
================ ========================
Visual           Light Level, Obscurement
Auditory         Wind, Sounds
Tactile          N/A
Olfactory        Wind*, Obscurement
Taste            N/A
Thermal          Temperature, Obscurement
Sonar/Ultrasound Sounds
Radar            Noise+
Astral           Background Count+
================ ========================

+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
| Standard Movement Multipliers   | Multiplier   | Standard movement multipliers can be used by any entity without the {Missing Movement Type} trait.                |
+=================================+==============+===================================================================================================================+
| Walking                         | 3            | Walking is the standard movement type, used for most travel overland. Swift movement of walking is running.       |
+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
| Swimming                        | 1            | Swimming is exclusively used for moving whilst submerged or at least floating on water or another liquid.         |
+---------------------------------+--------------+-------------------------------------------------------------------------------------------------------------------+
|Crawling                         | 1            | Crawling is only required when prone, and is the only movement type that can be used whilst prone.                |
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