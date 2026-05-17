Web sraper

  O čem je projekt

Python projekt zaměřený na Web scraping, volebních výsledků z roku 2017 z webu volby.cz. Skript automaticky stáhne data pro vybraný územní celek, zpracuje HTML strukturu a uloží výsledky jednotlivých obcí do CSV souboru.
  Postup

1. otevři si třeba visual studio code (pro python)
2. Nainstaluj potřebné knihovny ze souboru `requirements.txt`:

pip install -r requirements.txt

3. Spusť program:

web_scraper.py ----→ "vysledky.csv"



  Praktická ukázka

Použij tento odkaz:

https://www.volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=2&xnumnuts=2101

  Výstup

Program vytvoří soubor:

vysledky.csv

Tento soubor obsahuje výsledky voleb pro jednotlivé obce.



 Exportování

Pro správné zobrazení 

1. Otevři Excel  
2. Zvol Data → Načíst ze souboru (CSV)  
3. Vyber soubor vysledky.csv  

Poté se data zobrazí jako přehledná tabulka.
