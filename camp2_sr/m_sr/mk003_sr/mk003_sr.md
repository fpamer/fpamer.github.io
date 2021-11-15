# Proizvod

Program Proizvod se poziva iz menija: [Podaci](../m_sr.md) .

Proizvodi se proizvode u firmi. Imaju tehnologiju , normativ, itd..

Proizvod može biti gotov (krajnji ) proizvod , i ulazi u magacin gotovih proizvoda,
i može biti poluproizvod, koji je samo u magacinu pogona ili u medjufaznom lageru.

Za upis novog proizvoda ovde moramo zadati šifru proizvoda u celosti 
i pritisnuti taster "Upis šifre"

![Image](proizv001.jpg)

U gornjem delu prozora punimo podatke:

- Naziv
- Nivo (deo,sklop,usluga,set,sl.deo,paket)
- Jedinicu mere
- Tarifni broj
- Nomin. količinu za normativ (ako je uključen)

![Image](proizv002.jpg)

U donjem delo prozora:

- Pakovana količina
- Pakovana jedinica
- Predvidjeni magacin

Pritiskom na taster "Insert" ovde dodajemo tehnološke podatke proizvodnje.

Nivo prozvoda :
- 0 - materijal
- 1 - poluproizvod
- 2 - sklop ili proizvod 
- 3 - usluga
- 4 - set
- 6 - složen deo
- 7 - paket

Ako je nivo 1,2,3 , onda se taj proizvod lansira i dobije Radni Nalog. Usluga (nivo 3) ne mora imati normativ, medjutim tehnol. operacije moraju imati svi u ovoj grupi.

Ako je nivo 4,5,6 , onda se taj proizvod ne lansira, već se sastavlja od nižih nivoa u magacinu gotove robe, ili
se samo pakuje , ako je paket (nivo 7).

