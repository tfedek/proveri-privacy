# Proveri - Politika privatnosti

Poslednje azuriranje: jul 2026

## Ukratko

Proveri ne prikuplja, ne salje i ne cuva vase podatke. Sve ostaje na vasem uredjaju.

## Sta Proveri radi

Proveri je Chrome ekstenzija koja analizira sadrzaj emailova u Gmail-u i Outlook-u kako bi vam pomogla da prepoznate potencijalne phishing poruke.

## Kako funkcionise

- Analiza se vrsi lokalno, u vasem browseru
- Sadrzaj vasih emailova se ne salje na bilo koji server
- Ne postoji backend, baza podataka niti cloud servis

## Koji podaci se obraduju

Proveri automatski cita tekst i linkove otvorenog emaila radi trenutne procene rizika. Ovo se desava:

- Automatski, cim otvorite email (za indikator na ikonici)
- Kad kliknete na ikonicu ekstenzije (za detaljan prikaz u popup-u)

Svi ovi podaci postoje samo u memoriji browsera tokom analize. Rezultat (da li je email bezbedan, sumnjiv ili opasan) se privremeno cuva samo da bi se prikazao indikator na ikonici ekstenzije, i brise se kad zatvorite tab ili otvorite drugi email.

## Koji podaci se cuvaju

Nikakvi. Proveri ne koristi:

- Lokalni storage
- Kolacice
- Baze podataka
- Eksterne servise
- Analitiku
- Pracenje korisnika

## Koji podaci se salju

Proveri ne salje sadrzaj vasih emailova niti bilo koje licne podatke na eksterne servere. Ekstenzija ne komunicira ni sa jednim udaljanim serverom.

## Dozvole koje ekstenzija koristi

- `activeTab` - dodatni pristup trenutno otvorenom tabu kad kliknete na ikonicu (za popup prikaz)
- Content script na Gmail/Outlook domenima - automatski cita tekst i linkove otvorenog emaila radi trenutne procene rizika (za ikonicu-indikator), nezavisno od toga da li ste kliknuli na ekstenziju

## Deca

Proveri ne prikuplja podatke ni od koga, ukljucujuci decu.

## Promene politike

Ako se ova politika promeni, azuriraemo datum na vrhu stranice. Posto ne prikupljamo podatke, promene mogu biti samo u smeru dodavanja novih funkcionalnosti - u tom slucaju cemo jasno navesti sta se promenilo.

## Kontakt

Za pitanja o privatnosti: proveri@fedek.dev
