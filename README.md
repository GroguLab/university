# university

Egyetemi tanulási segédanyagok – böngészőben futó, önálló HTML fájlok.

**Élő oldal:** https://grogulab.github.io/university/

## Tartalom

### 2026/27. őszi félév

| Tárgy | Anyag | Link |
| --- | --- | --- |
| Iskolák és tanuló közösségek | Fogalomkártyák (20 kártya, ZH-fogalmak) | [megnyitás](https://grogulab.github.io/university/iskolak-es-tanulokozossegek/fogalomkartyak.html) |

## Felépítés

```
index.html                                  landing page, innen nyílnak az anyagok
iskolak-es-tanulokozossegek/
  fogalomkartyak.html                       20 megfordítható fogalomkártya
```

Minden anyag egyetlen, függőség nélküli HTML fájl: külső szkript, CDN és build-lépés nélkül működik. Elég megnyitni a böngészőben (vagy letölteni és offline megnyitni).

## Új anyag hozzáadása

1. Az új HTML fájl a tárgy mappájába kerül (új tárgynál új mappa, ékezet nélküli, kötőjeles névvel).
2. Az `index.html`-ben a tárgy `<ul class="sets">` listájába bekerül egy új `<li>` a linkkel.
3. Ha új tárgy, az `index.html`-be egy új `<section class="course">` blokk kerül.
