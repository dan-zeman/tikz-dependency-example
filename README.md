# tikz-dependency-example

Tato složka je určena pro dočasné soubory v LaTeXu, kde vyrábím příklady stromů v tikz-dependency, určené ke vložení do jiných dokumentů, např. v Libre Office. LaTeX je proto nastaven tak, aby vytvořil PDF pouze tak velké, jak je potřeba pro daný strom, bez pevné velikosti stránky a bílého místa na ní.

Výsledné PDF se dá vložit jako obrázek do dokumentu Libre Office, ale není to perfektní. Libre Office použije jiný font, někdy má problémy se správným změřením vzdáleností mezi uzly a teď se mi stalo, že po vložení třetího obrázku se ty první dva přestaly zobrazovat. Možná je to tím, že všechny tři vkládám ze stejného souboru, jehož obsah se mezitím změnil.

Alternativně lze otevřít PDF v Inkscape (pomocí externí knihovny, tj. Poppler/Cairo import) a uložit ho jako rozšířený metasoubor (.emf). Ten lze bez problémů načíst jak do dokumentů Libre Office, tak Microsoft Office (na rozdíl od souborů SVG, s jejichž načítáním je problém).
