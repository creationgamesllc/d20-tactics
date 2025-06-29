# Formations of Creatures

Formations simplify record-keeping and accelerate gameplay when managing large numbers of identical creatures. Generally, formations impose more restrictions than managing creatures individually, making them most suitable for larger combats.

Formations will never consist of unique characters such as Player Characters. They are for minions, mobs, and military units.

## Definition

*A formation consists of one or more creatures with identical stat blocks, sharing a restrictive game state.*

*The DM or scenario defines which creatures begin combat in formation. Formations can only be altered or disbanded by DM decision.*

## Quick Reference

1. Creatures in a formation are identical except for their position and status as alive / dying (equivalent to being at 0 HP) / dead. They share a stat block and all game conditions and status. They act on a shared turn on a shared initiative.

***Example***: *A formation of 8 Goblin Archers each occupy a different square on a battlegrid but are otherwise the same. Either they all have the fear condition or none of them do, either they all are subject to the Bless spell or none are, and so on.*

2. The creatures have a shared HP pool equal to their individual maximum HP multiplied by the number of creatures in the formation.

***Example***: *The goblins have an individual max of 10 HP each and there are 6 of them, so the HP pool of the formation is 60 HP.*

3. When the shared HP pool decreases to multiples of individual creature maximum HP, creatures damaged that turn creatures begin dying, one per multiple of the maximum of HP decreased.

***Example***: *Some of the archers are attacked and they take a total of 21 damage, reducing their HP pool to 39 HP. This is a reduction from their maximum by just over double their individual max HP of 10 but less than three times, so 2 goblins begin dying and must make a modified form of death saving throw (described in the detailed rules) at the end of each turn.*

4. Creatures move and act individually during a shared turn but must remain within their movement speed of each other and take identical actions, bonus actions, and reactions with identical choices other than targets.

***Example***: *On their turn the goblins each move 30 feet, both beginning and ending in relatively tight formation where each goblin is within 30 feet of each other goblin. Each occupies a distinct square on the battle grid at all times. After movement, 5 of the surviving goblin archers have a clear shot against an enemy, but one is behind total cover. 5 goblin archers attack and one must decline to act.*

5. If half or more creatures in formation would gain a status, condition, or other game effect, the entire formation gains it; otherwise, none do. Creatures in formation always have resources (such as spells slots or ability use per day) equal to the creature in the formation with the least.

***Example***: *A wizard casts Hypnotic Pattern on the goblin formation. The area of the spell overlaps 2 of the surviving 4 goblins. They make a shared Wisdom saving throw (see the detailed rules) and fail. Since more than half of the goblins would suffer the effects of the spell, they all do.*

## Detailed Rules

## Initiative

1. Creatures in formation share one initiative roll. Adjustments to initiative apply only if they affect at least half the creatures in formation, in which case they apply to all of them.

### Actions and Bonus Actions

2. Each creature in formation must choose identical actions or bonus actions each turn, except for choosing different targets for attacks, magic, or shove actions.

### Movement and Positioning

3. Creatures in a formation move individually during their shared turn, obeying all normal rules regarding movement.

4. Formations of creatures must remain in a close formation where no two creatures are more than their movement speed apart from one another.

5. If they are separated, all creatures in the formation can only perform the dash, dodge, or disengage actions and move toward the creature in the direction of the creature they are farthest from.

6. If they return to proximity to one another after or during their movement, they can then act as normal.

7. A player may not voluntarily move creatures in a way that they end their turn out of formation.

8. Position-based effects like cover or difficult terrain apply individually rather than collectively.

### Status Conditions

9. Status conditions or effects apply to all creatures in formation if at least half have that condition or effect at the end of a turn. Otherwise, none of the creatures gain or retain the condition. This includes all statuses that in any way alter a creature's game state, whether they are helpful or harmful.

***Example***: A cleric casts Bless on three creatures in a formation of 5. All 5 creatures gain the benefits of the spell. They are attacked by multiple attacks with the topple weapon mastery ability. Two creatures are hit and are knocked prone, but at the end of the turn only those two are prone, so none of them are.

### Hit Points (HP) and Temporary HP

10. Formations begin with an HP pool equal to individual creature maximum HP multiplied by the number of creatures.

11. Temporary HP pools may be refreshed entirely if one or more creatures gain temporary HP simultaneously or during one turn. The new pool equals the sum of the temporary HP gained by the creatures in one turn.

12. Healing is added to the HP pool, limited by the maximum HP times the number of living creatures in formation.

13. A healing effect may not restore more HP to a formation than the number of creatures affected multiplied by the individual maximum HP.

### Damage and Death

14. Damage first subtracts from temporary HP, then from the formation's shared HP pool.

15. A single damage source can't exceed the combined maximum HP of affected creatures.

16. Formations with half or fewer HP are considered bloodied.

17. Creatures begin dying when shared HP falls to or below multiples of individual HP maximums. This condition applies individually, not collectively.

18. Determine dying creatures by reducing formation size until the HP pool exceeds the combined HP of the remaining creatures.

**Example:** A formation of six goblins (10 HP each, 60 total) loses HP to 50 (one goblin dying), 41 (still one dying), or 28 (three goblins dying).

19. The DM or controlling player chooses dying creatures from those damaged. Additional dying creatures are chosen freely from unaffected members in the unusual circumstance where it would be necessary.

### Dying and Death

20. Dying creatures from formations must each make a separate standard DC 10 Constitution saving throws at the end of their turn. One failure results in death. Do not track successes, the creature must be stabilized by an external source.

21. Dying creatures instantly die if separated by more than their movement speed from the most distant creature in the formation.

22. Stabilized creatures separated from the formation remain alive but cannot be returned to action by the formation regaining HP if separated.

23. Stabilized or healed creatures don’t rejoin combat unless the shared HP pool allows for revival as described below.

24. Dying or stabilized creatures rejoin combat if healing raises the HP pool sufficiently to increase the HP pool above a higher multiple of the individual HP maximum.

25. Dying or stabilized creatures rejoin until the number of active creatures in the formation multiplied by the individual hp maximum exceeds the HP pool or until there are no more creatures that are not dead remaining.

26. Dying creatures rejoin the formation before stabilized ones do.

***Example***: *After losing being reduced to 28 HP, three goblins in the formation begin dying. At the end of their turn they individually make DC 10 constitution saving throws. One fails and immediately dies.*

*Before their next turn a cleric casts healing word on one goblin in the formation (either alive or dying) and makes a medicine check to stabilize one of the dying goblins. Healing word restores 5 HP, raising the formation to 33 HP. One is stabilized but still down, the other stands up to rejoin their comrades in battle.*

27. Revived creatures from spells or similar effects are considered stabilized unless additional healing conditions for returning to combat are met.

### Shared D20 Checks

28. Formation members make a single shared roll (using the worst bonuses and conditions if they differ) for identical D20 checks or saving throws arising from the same trigger (such as all saving to avoid damage from a Fireball spell, or all making an Athletics check to climb a cliff). The exception to this is the modified death saving throw described above and attack rolls.

### Reactions

29. All creatures in formation must use identical reactions within a turn or decline to react. If they do, no creature in the formation may take a further reaction until the beginning of the formation's next turn.

### Equal Resources

30. All formation members equalize their available resources (spell slots, items, abilities) to the lowest available number held by any individual.

## Movement Trays

*Movement trays may visually assist in handling formations but have no game effect and do not bind creatures' positions to the tray*

## Interaction with Chaos Initiative

1. Formations receive a single shared order.

2. References to a turn in rules 7, 8, 11, and 29 refer to any single creature or formation's initiative position in the shared Chaos Initiative turn.