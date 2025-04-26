# Deadlock - Prevod na Srpski (Latinica)

Ovo je repo za prevod Valve-ove igre Deadlock na srpski jezik. Ovo radim uglavnom za sebe, koristeći AI i Python skripte da ubrzam proces.

Primarno sam napravio ovaj repozitorijum da imam **online backup** za svoj prevod. Dešava se da kad igra dobije update, ume da obriše ili prepiše lokalne fajlove prevoda, pa da ne bih morao ponovo da ih ubacujem ili pravim, lakše mi je da ih držim ovde. Pošto već postoji online, **što da ne bude public ako još nekom zatreba?** :)

Cilj je da se prevede što više tekstualnih delova igre, ali pošto radim sam i prvenstveno za sebe, projekat će napredovati tempom kojim ide. Ne tražim aktivno pomoć, ali slobodno koristite fajlove ako vam znače.

## Status Prevođenja

Evo dokle se stiglo:

* ✅ **Interfejs (UI):** Prevedeno.
* ✅ **Item Shop:** Prevedeno.
* ✅ **Opisi itema:** Prevedeno.
* ⏳ **Opisi heroja:** U planu, biće prevedeno.
* ❌ **Imena heroja:** Neće biti prevođena. Iskreno, zvuči čudno i kontroverzno je prevoditi imena likova. Bolje da ostanu originalna.
* ❌ **Glasovi (Voice Acting):** Nije moguće prevesti, to su audio fajlovi.

Generalno, fokus je na tekstualnim delovima igre.

## Kako Instalirati Prevod

Lagano je, prati ove korake:

1.  **Skini fajlove:**
    * Idi na vrh ovog GitHub repozitorijuma.
    * Klikni na zeleno dugme `<> Code`.
    * Izaberi `Download ZIP`.
    * (Alternativa za iskusnije: `git clone https://github.com/tvoj-username/tvoj-repozitorijum.git`)

2.  **Raspakuj arhivu:**
    * Ako si skinuo ZIP fajl, raspakuj ga negde na svom kompjuteru gde ćeš ga lako naći.

3.  **Pronađi folder igre:**
    * Nađi gde ti je instaliran Deadlock na kompjuteru.
    * Unutar glavnog foldera igre, treba da nađeš putanju sličnu ovoj: `...\Deadlock\game\citadel\resource\localization`

4.  **Kopiraj foldere prevoda:**
    * Otvori folder koji si raspakovao u koraku 2.
    * Unutra ćeš videti foldere kao što su `citadel_attributes`, `citadel_gc`, `citadel_heroes`, itd.
    * **Selektuj SVE te foldere** i kopiraj ih (Ctrl+C ili desni klik -> Copy).

5.  **Nalepi foldere u igru:**
    * Idi u `...\localization` folder igre koji si pronašao u koraku 3.
    * Nalepi kopirane foldere ovde (Ctrl+V ili desni klik -> Paste).

6.  **Podesi Steam Launch Options (Obavezno!):**
    * Otvori Steam Library.
    * Klikni desnim tasterom miša na Deadlock i izaberi `Properties...`.
    * Potraži polje `Launch Options` na dnu.
    * U to polje ukucaj **tačno ovako**: `-language serbian`
    * Ovo govori igri da učita fajlove za srpski jezik pri pokretanju.

7.  **Pokreni igru:**
    * Startuj Deadlock normalno preko Steam-a. Igra bi sada trebalo da prikazuje prevedeni tekst.
    * *Napomena:* Unutar same igre verovatno **nećeš videti** opciju za odabir srpskog jezika u meniju za podešavanja jezika. Igra koristi fajlove zahvaljujući `-language serbian` komandi koju si uneo u Steam-u.

**Važna napomena:** Fajlovi u ovom repozitorijumu se zovu npr. `citadel_attributes_serbian.txt`. Originalni fajlovi igre (npr. engleski) se zovu `citadel_attributes_english.txt`. Ovaj prevod **ne menja** originalne fajlove, već dodaje nove fajlove za srpski jezik.

## Napomene i Potencijalni Problemi

* **Kvalitet prevoda:** Pošto se prevod radi uz veliku pomoć AI, moguće su povremene greške, nespretne formulacije ili čudni prevodi. Trudim se da pregledam i ispravim koliko stignem.
* **Ažuriranja igre:** Kada Valve izbaci novi update za Deadlock, postoji šansa da će se fajlovi za lokalizaciju promeniti. To može dovesti do toga da prevod postane nekompletan ili da se određeni delovi vrate na engleski dok ne ažuriram fajlove u ovom repozitorijumu. Biće potrebno malo strpljenja (i meni da opet uploadujem ako treba).
* **Kompatibilnost:** Prevod je rađen za trenutnu verziju igre. Nema garancije da će raditi sa budućim ili prošlim verzijama bez izmena.
* **Pop-up u podešavanjima (Settings):** Postoji poznat problem - svaki put kada uđeš u meni za podešavanja (Settings) u igri, iskočiće poruka koja traži da restartuješ igru kako bi se primenile promene jezika, *čak i ako nisi ništa menjao*. Ovo se dešava jer srpski nije zvanično dodat kao jezik u dropdown meniju igre, pa igra to registruje kao promenu. **Samo klikni "OK" ili zatvori tu poruku i ignoriši je.** Prevod će i dalje raditi normalno van menija za podešavanja.

## Licenca

Ovaj prevod je objavljen pod **WTFPL – Do What The Fuck You Want To Public License**.

[![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png)](http://www.wtfpl.net/)

Ukratko: **Radi šta god hoćeš sa ovim fajlovima.** Možeš da ih kopiraš, menjaš, deliš, koristiš u svom projektu, šta god. Nema na čemu.
