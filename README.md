# FSI VUT Šablona závěrečných prací v systému LATEX
Šablona závěrečných prací v systému LATEX pro Fakultu strojního inženýrství na Vysokém učení technickém v Brně, která vznikla jako bakalářská práce v akademickém roce 2022/2023 na Ústavu automatizace a informatiky.

Šablona závěrečné práce je tvořena následujícími soubory:

1. `nastaveni.tex` - soubor pro zadání základních údajů o závěrečné práci (druh závěrečné práce, název, odkaz na elektronickou publikaci, autor, vedoucí, ústav, město, rok obhajoby, datum odevzdání a jazyk zpracování). Dále je nastavováno formátování odstavců a číslování obrázků, tabulek a rovnic.

2. `zaverecna_prace.tex` - hlavní pracovní soubor, který se překládá překladačem `LuaLaTeX` a `BIBTeX`. V souboru se aktivuje samotná šablona, aktivují se volitelné externí balíčky, vkládá se titulní strana a zadání. Do tohoto souboru uživatel také přímo vepisuje úvodní textové náležitosti (abstrakt, klíčová slova, prohlášení a poděkování), vkládá jednotlivé kapitoly a probíhá generování obsahů.

3. `sablona.sty` - balíček, zdrojový kód šablony.

4. `citace.bib` - soubor pro vkládání zdrojové textu použité literatury pro program `BIBTeX`.

5. `czplain.bst` - stylový balíček pro program `BIBTeX`, který upravuje styl citací dle ČSN ISO 690.

6. `zaverecna_prace.pdf` - výsledný PDF dokument celé závěrečné práce.	

**Pomocné adresáře:**

1. `fonty` - složka se zdrojovými soubory VUT fontů použitých v šabloně.

2. `kapitoly` - složka pro ukládání souborů ve formátu `.tex` s textovým obsahem jednotlivých kapitol. Kapitoly *ÚVOD* a *ZÁVĚR* pojmenovat jako `00_uvod.tex` a `00_zaver.tex`.

3. `loga` - složka s logy fakulty a univerzity, které jsou použity v šabloně.

4. `obrázky` - složka pro ukládání obrázků použitých v textu práce.

5. `soubory` - složka pro titulní stranu a zadání ve formátu `.pdf`. Soubory pojmenovat jako `titulni_strana.pdf` a `zadani.pdf`.

Soubory s příponami `.aux`, `.bbl`, `.blg`, `.lof`, `.log`, `.lot`, `.out` a `.toc` jsou soubory vytvářené systémem LATEX během překladu zdrojového textu. Do těchto souborů si systém ukládá potřebná data používaná pro generování výsledného PDF dokumentu.
