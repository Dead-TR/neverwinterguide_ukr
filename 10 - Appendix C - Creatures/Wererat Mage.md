---
name: Щуролак Чаклун
slug: wererat-wizard-page
---

```Monster {.two-column}
name: Щуролак Чаклун
slug: wererat-wizard
size: Середній
type: Гуманоїд
alignment: Будь-який світогляд
ac: 12 (15 з магічною робою)
hp: 49 (11d8)
speed: 30 футів.
str: 9
dex: 14
con: 11
int: 17
wis: 12
cha: 11
saves: Інтилект +6, Мудрість +4
skills: Магія +6, Історія +6
damageImmunities: забійні, пронизувальні та рублячі немагічні атаки непосрібленою зброєю
senses: темнозір 60 ft., пасивне Сприйняття 11
languages: будь-які три мови й злочинний жаргон (не може говорити в щурячій формі)
challenge: 5
environments: Міське
traits:
  - name: Гострий нюх
    description: Щуролак має переваги при перевірках Мудрості(Сприйняття), що покладаються на нюх.
actions:
  - name: Мультиатака (Лише в гуманоїдній або гібридній формі)
    description: "Щуролак може здійснити три атаки Магічного Вибуху."
  - name: Магічний Вибух (Лише в гуманоїдній або гібридній формі)
    description: "Ближня або Дальня атака Магією: +6 до попадання, досяжність 5 футів. або дальність 120 футів., одна ціль. Наносить: 19 (3d10 + 3) силової шкоди."
  - name: Укус (Лише в щурячій або гібридній формі)
    description: "Атака Зброєю Ближнього Бою: +5 до попадання, досяжність 5 ft., одна ціль. Наносить: 4 (1d4 + 2) пронизувальної шкоди. Якщо ціль гуманоїд -- вона мусить зробити успішний кидок Статури, інакше набуде прокляття щуролачої лікантропії"
  - name: Чаклування (Лише в гуманоїдній або гібридній формі)
    description: "Щуролак зачитує одне з наступних заклинань, використовуючи Інтилект як магічної характеристики (збереження заклинання СК 14):


        За бажання: <i>танцюючі вогні</i>, <i>магічна рука</i>, <i>prestidigitation</i>

        2/day each: <i>fireball</i>, <i>mage armor</i>, <i>unseen servant</i>, <i>ice storm</i>"
bonus-actions:
  - name: Change Shape
    description: "Щуролак transforms into a rat-humanoid hybrid, into a giant rat, or back into its humanoid form. Its statistics, other than its size, are the same in each form. Any equipment it is wearing or carrying isn't transformed. It reverts to its true form if it dies."
image: WereratMage.jpg
token: WereratMageToken.png
column-after: actions
column-after-property: Bite (Rat or Hybrid Form Only)
```