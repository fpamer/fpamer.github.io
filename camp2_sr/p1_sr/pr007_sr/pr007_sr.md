# Kalk-ponude

Program "Kalk-ponude" se poziva iz menija [Planiranje](../p1_sr.md)

Program radi kalkulaciju dokumenta:

- Ponude
- Narudžbe

Posle izbora dokumenta program kalkuliše elemente dokumenta:

![Image](kalk_pon01.jpg)

Klik na proizvod nam daje prikaz kalkulacije tog proizvoda u
posebnom prozoru.

Troškove proizvoda dobijamo kao zbir:
- materijalnih
- radnih i
- indirektnih troškova.

Indirektni troskovi su:
```
tr_ind: (tr_mat x koef_indmat) + (tr_izr x koef_indrad)
```
Koeficijenti su zadati kod parametara firme na primer:
```
koef_indmat: 0.15
koef_indrad: 0.30
```

Kod exporta podataka imamo i mogućnost množenja 
sa koeficijentom prodaje.
