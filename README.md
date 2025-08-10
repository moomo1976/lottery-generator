# Generátor čísel pro Sportku

Tento projekt je interaktivní webová aplikace pro generování náhodných čísel pro českou loterii Sportka. Aplikace je vytvořena pomocí HTML, CSS a čistého JavaScriptu a nabízí několik pokročilých funkcí pro personalizované generování čísel.

## Funkce

- **Generování více sloupců:** Možnost vygenerovat najednou 1 až 8 sloupců s čísly.
- **Různé metody generování:**
  - **Náhodná:** Klasické losování 6 unikátních čísel z 49.
  - **Podle znamení:** Generuje čísla na základě "šťastných" čísel přiřazených ke každému znamení zvěrokruhu.
  - **Podle data narození:** Využívá jednoduchý numerologický algoritmus k vytvoření osobních čísel z data narození.
- **Informace o losování:** Aplikace automaticky zobrazuje datum příštího losování Sportky (středa, pátek, neděle).
- **Export a sdílení:**
  - **Kopírovat do schránky:** Snadno zkopíruje všechna vygenerovaná čísla v přehledném textovém formátu.
  - **Odeslat e-mailem:** Otevře výchozí e-mailový klient s předvyplněnými čísly pro snadné odeslání.
- **Responzivní design:** Moderní a čistý vzhled, který se přizpůsobí jakémukoliv zařízení (mobil, tablet, desktop).

## Jak použít

1.  Otevřete soubor `lottery_generator.html` v jakémkoliv moderním webovém prohlížeči.
2.  V horní části si nastavte požadovaný počet sloupců a metodu generování.
3.  Pokud zvolíte generování podle znamení nebo data narození, vyberte příslušnou volbu.
4.  Klikněte na tlačítko **"Generovat čísla"**.
5.  Vygenerovaná čísla se zobrazí v kartách. Můžete je zkopírovat nebo odeslat e-mailem pomocí tlačítek pod nimi.

## Použité technologie

- **HTML5:** Pro strukturu stránky.
- **CSS3:** Pro moderní vzhled, stylování a responzivitu (včetně CSS Grid a Flexbox).
- **JavaScript (ES6+):** Pro veškerou logiku aplikace, včetně generování čísel a interaktivity.
