# Chaos Initiative

*Digital tools are suggested for this rules module, a sample Python Jupyter notebook for quickly generating an initiative order is included, and the author of these rules is working on a more powerful tool.*

## Writing orders

At the start of combat and at the beginning of each round, each game participant including the DM write down orders for each creature or formation of creatures under that player or DM's control.

A player writes down a creature's movement, action, bonus action, object interactions, and reaction for the round.

Orders **cannot** include *general conditionals* of the form "if this then do that or else to this" or any other similar phrasing. However, each of movement, action, bonus action, and object interaction may include at most one explicit use of "or else" after describing an action with a target or reference that may not exist, rendering the action impossible.

A player can only write up to two potential reactions for the turn and must include a trigger for each.

**For instance:**

"The orc warrior moves 30 feet toward the formation of soldiers and makes a melee greataxe attack against an adjacent enemy or else throws a javelin at the closest enemy within range"

"The fighter moves adjacent to the closest enemy within its movement or else 30 feet west and makes a melee longsword attack against an adjacent enemy or else readies an attack for when an enemy moves into an adjacent square"

"The elf paladin moves adjacent to the animated armor and attacks, using divine smite on a hit or else misty step 30 feet to the other side of the large tree after the attack action"

"The wizard moves 30 feet toward the cleric, her familiar flies adjacent to the cleric, she uses a magic action to cast Cure Wounds with Magic Initiate delivered through the familiar. She uses her reaction to cast Counterspell if a damaging spell targeting more than one ally is cast by an enemy in range or Protection from Elements if she is the target of elemental damage other than a cantrip."

## The Expanded Ready Action

A readied action may include movement or a bonus action if you have movement or a bonus action left for the turn to ready.

"The formation of militia archers ready an action, when the 8 southernmost spaces on the south of the closest hill are open, they move into those positions and then make shortbow attacks against the closest enemy within range or else dodge"

## Formations

Formations receive a single order.

Orders may include "enemy (or formation)" such as:

"The formation of soldiers moves South 10 feet then surround the closest bloodied enemy (or formation) or else move a further 20 feet south and make melee attacks against adjacent enemies or else throw javelins at the closest enemy."

## Resolving the Round

Every turn, after orders have been submitted, roll initiative for every creature in the combat.

All creatures turns begin simultaneously.

Note all specified reactions before resolving the turn.

In order of descending initiative, resolve the turn one creature at a time resolving each order completely, with formations acting on the same initiative as usual.

The turn ends simultaneously for all creatures at the end of the round.

*Multi-attack*: If a creature multiattacks and the target of the attack dies between attacks. The other attacks are automatically used on the closest enemy in range, if any. If the attack was melee and there are no creatures in melee range, and the creature has an available ranged attack and with targets in (short or long) range, complete the attack with ranged attacks against the closest enemy in range.

*Opportunity attack*: If a creature does not specify any other reaction, they are assumed to take the first available opportunity attack.

*Ambiguous creature targets*: If an order specified a target creature such as "nearest enemy" that could be multiple possible enemies, decide the tie by selecting the creature with the latest position in the initiative order.