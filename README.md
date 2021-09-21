# ist2021v2

APRIL 2021 IST
Napomene:
Pre početka svakog zadatka (sem prvog) pravi se nova grana sa brojem
tog zadatka.
Nakon završetka zadatka, snimaju se promene na mrežnom
repozitorijumu uz
odgovarajuću poruku. Izmene na istom zadatku snimati kao posebne
verzije. Potrebno je uraditi spajanje grane završenog zadatka sa
master granom.
Projektni zadaci:
1. Napraviti novi repozitorijum naziva ist2021. Uraditi initial
commit za mrežni repozitorijum koji će sadržati fajl
proizvodi.xml.
2. U fajlu proizvodi.xml kreirati podatke o Proizvodima u veb prodavnici.
Proizvod je opisan sledećim elementima:
Kategorija proizvoda – sadrži obavezno jednu od
predefinisanih kategorija (npr. laptopovi, monitori, stolovi,
stolice…)
Cena – iznos. Cena je dodatno opisana atributom valuta koji
podrazumevano označava dinare.
Tekst oglasa – isključivo tekstualni sadržaj bez umetnutih
elemenata.
Oznaka (tag) oglasa – jedan proizvod može imati više
oznaka. Oznaka bliže opisuje proizvod i nema ograničen
skup vrednosti. Oznake nisu u hijerarhijskoj relaciji
međusobno.
Akcija proizvoda –Akcija je dodatno opisana atributom
cena ako je na akciji koliko sada iznosi njegova cena.
Takođe ima atribut datum isteka do kada važi akcija.
Jedan proizvod na akciji može biti više puta i svaki put
imati drugu cenu.
3. Napraviti DTD fajl koji će proveravati podatke iz fajla
proizvodi.xml uz maksimalno stroga pravila u skladu sa
navedenim tekstom.
4. Napraviti XSD fajl koji će omogućiti dodatna ograničenja
Tekst oglasa mora imati najmanje 10 a najviše 180 karaktera.
Cena ne može biti negativna.
Maksimalan broj Oznaka je 5.
5. Koristeći NodeJS napisati aplikaciju koja će realizovati prikaz
(sa filtriranjem), kreiranje, brisanje i promenu proizvoda
(podaci se čuvaju u json formatu).
6. Za navedeni server napraviti klijent aplikaciju koja će testirati rad
