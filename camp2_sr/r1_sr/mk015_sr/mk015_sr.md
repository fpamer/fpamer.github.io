# Izveštaji-OS

Program "Izveštaji-OS" se poziva iz menija [Alati](../r1_sr.md)

![Image](izv_os01.jpg)

U okviru ovih izveštaja imamo "Knjiženje amortizacije".

Moramo izabrati datum obrade i knjigovodstveni oblast:

- 1-knjigov
- 2-poreska

Taster "Knjiženje" kalkuliše i dodaje red anortizacije na svaku karticu osnovnog sredstva.

Amortizaciju računamo množenjem broja punih meseca proteklih od 
zadnje amortizacije (ili nabavke) sa procentom amortizacije i sa
osnovicom za amortizaciju i delimo sa 12.

Za degresivni metod je osnovica ostatak vrenosti. Taj metod važi i kod knjigov.amortizacije.
Za proporcionalni metod je osnovica nabavna vrednost.

Poresku amortizaciju kalkuliše u dve etape, posebno za 
- Pojedinačno (nabavka od 01.01.2019, pojedinačna kalkulacija)
- Grupno (na starim karticama, ali i ovde imamo i pojed.vrednosti)

Taster "Brisati" briše svaku amortizaciju izabrane oblasti za taj datum.

Kod knjigovodstvene amortizacije imamo samo jedno štampanje.

Kod poreske amortizacije imamo četiri štampanja zavisno od načina i od metode amortizacije.

Uporedni pregled prikazuje i knjigovodstvenu i poresku amortizaciju,
odn. manju vrednost, koja će biti knjižena.
