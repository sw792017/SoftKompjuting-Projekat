## SoftKompjuting-Projekat

### STA

Potrebno je kreirati model za klasifikacije vremenskih prilika na osnovu slika u
4 klase (izlazak sunca, oblacno, suncano i kisovito) sa bar 70% tacnosti


### KAKO:

1) Ucitavanje labela i slika preko "pandas" biblioteke
2) Resizovanje svih slika na rezoluciju 400x400 i konvertovanje u grayscale
3) Sve slike provlacimo kroz HOG feature descriptor
4) Ubacimo sve labele i izmenjene slike u SVC model
5) Ocenjujemo dobijen model nad podacima namenjenim za testiranje


### REZULTAT:

Model je pokrenut za 225 slika iz skupa za testiranje gde je podtigao preciznost od 79.11%
