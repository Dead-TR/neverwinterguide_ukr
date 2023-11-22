---
name: Грозовий Смерч
slug: storm-gyre-page
---

```Monster {.two-column}
name: Грозовий Смерч
slug: storm-gyre
size: Середній
type: Елементаль
alignment: Істино Нейтральний
ac: 18 (природній захист)
hp: 135 (9d10 + 35)
speed: 0 фут., політ 60 фут. (невагомість)
str: 10
dex: 20
con: 12
int: 5
wis: 14
cha: 5
senses: темнозір 60 фут., пасивна Уважність 12
damageResistances: блискавка, грім; bludgeoning, piercing, and slashing from nonmagical attacks
damageImmunities: poison
conditionImmunities: exhaustion, grappled, paralyzed, petrified, poisoned, prone, restrained, unconscious
languages: Auran
challenge: 8
token: StormGyreToken.png
image: StormGyre.jpg
traits:
  - name: Air Form
    description: "The Грозовий Смерч can enter a hostile creature's space and stop there. It can move through a space as narrow as 1 inch wide without squeezing."
actions:
  - name: Percuss
    description: "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 19 (2d10 + 8) thunder damage, and the target must succeed on a DC 13 Constitution saving throw or be stunned until the end of the gyre's next turn."
  - name: Conduction
    description: "The Грозовий Смерч picks a target within 60 feet. That target, and all other targets within 10 feet of that target, must make a DC 14 Dexterity saving throw. All targets take 22 (5d8) lightning damage on a failed save, or half as much on a successful one."
column-after: actions
column-after-property: Percuss
```