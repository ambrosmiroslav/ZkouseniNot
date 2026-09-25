# Notová zkouška

Toto je statická HTML aplikace pro procvičování not na notové osnově.

## Funkce

- Režim 1: žák vidí jednu notu na osnově s klíčem a musí kliknout na správnou notu na virtuální klávesnici.
- Režim 2: žák vidí název noty a prázdnou osnovu s klíčem. Pomocí tlačítek Nahoru a Dolů umístí notu na správné místo a potvrdí volbu.
- Nastavení obtížnosti před spuštěním:
  - výběr klíče: houslový, basový
  - výběr oktáv: nulačárková, jednočárková, dvoučárková (tři oktávy v celku)
  - možnost zapnout křížky a béčka
  - noty se vykreslují na správné pozice na pěti linkách nebo na pomocných linkách nad/pod osnovou

## Soubor aplikace

- `index.html` – kompletní obsah aplikace ve statickém HTML s CSS a JavaScript

## Spuštění

Stačí otevřít soubor `index.html` v prohlížeči. Pro lokální testování je možné spustit také jednoduchý server, například:

```bash
python -m http.server 8000
```

Potom otevřít v prohlížeči adresu:

```text
http://localhost:8000/
```

## Nahrání na webhosting

Jednoduše nahrajte soubor `index.html` na hosting, který podporuje statické HTML stránky. Pokud hosting používá složku pro web, stačí nahrát soubor do kořenové složky webu.

## Poznámka

Aplikace nevyžaduje žádný backend ani databázi. Je plně statická a může být nahrána na běžný webhosting nebo GitHub Pages.
