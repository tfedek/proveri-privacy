# Proveri - Politika privatnosti

Poslednje ažuriranje: jul 2026

## Ukratko

Proveri ne prikuplja, ne šalje i ne čuva vaše podatke. Sve ostaje na vašem uređaju.

## Šta Proveri radi

Proveri je Chrome ekstenzija koja analizira sadržaj emailova u Gmail-u i Outlook-u kako bi vam pomogla da prepoznate potencijalne phishing poruke.

## Kako funkcioniše

- Analiza se vrši lokalno, u vašem browseru
- Sadržaj vaših emailova se ne šalje na bilo koji server
- Ne postoji backend, baza podataka niti cloud servis

## Koji podaci se obrađuju

Proveri automatski čita tekst i linkove otvorenog emaila radi trenutne procene rizika. Ovo se dešava:

- Automatski, čim otvorite email (za indikator na ikonici)
- Kad kliknete na ikonicu ekstenzije (za detaljan prikaz u popup-u)

Svi ovi podaci postoje samo u memoriji browsera tokom analize. Rezultat (da li je email bezbedan, sumnjiv ili opasan) se privremeno čuva samo da bi se prikazao indikator na ikonici ekstenzije, i briše se kad zatvorite tab ili otvorite drugi email.

## Koji podaci se čuvaju

Nikakvi. Proveri ne koristi:

- Lokalni storage
- Kolačiće
- Baze podataka
- Eksterne servise
- Analitiku
- Praćenje korisnika

## Koji podaci se šalju

Proveri ne šalje sadržaj vaših emailova niti bilo koje lične podatke na eksterne servere. Ekstenzija ne komunicira ni sa jednim udaljenim serverom.

## Dozvole koje ekstenzija koristi

- `activeTab` - dodatni pristup trenutno otvorenom tabu kad kliknete na ikonicu (za popup prikaz)
- Content script na Gmail/Outlook domenima - automatski čita tekst i linkove otvorenog emaila radi trenutne procene rizika (za ikonicu-indikator), nezavisno od toga da li ste kliknuli na ekstenziju

## Deca

Proveri ne prikuplja podatke ni od koga, uključujući decu.

## Promene politike

Ako se ova politika promeni, ažuriraćemo datum na vrhu stranice. Pošto ne prikupljamo podatke, promene mogu biti samo u smeru dodavanja novih funkcionalnosti - u tom slučaju ćemo jasno navesti šta se promenilo.

## Kontakt

Za pitanja o privatnosti: proveriextension@gmail.com
