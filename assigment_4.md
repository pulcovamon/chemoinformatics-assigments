# Assignment 4
## Summary of AlphaFold article
### Zvolený článek: [AlphaFold is running out of data — so drug firms are building their own version](https://www.nature.com/articles/d41586-025-00868-9)

- Článek nejprve představuje AlphaFold 3:
    - AlphaFold je revoluční nástroj pro predikci 3D struktury proteinů.
    - Verze AlphaFold 3 umí navíc modelovat i interakce proteinů s jinými molekulami, např. léčivy.
    - Využívá veřejná data z databáze PDB a v open-source variantě je volně přístupný.

- Poté upozorňuje na problém:
    - Veřejná databáze PDB obsahuje především biologické interakce (např. ATP), ale jen málo dat o vazbách na léčiva.
    - I když AlphaFold 3 funguje pro vývoj léčiv poměrně dobře, predikce těchto interakcí stále není dostatečně přesná.
    - Farmaceutické firmy mají mnoho těchto dat interně, ale do PDB přispívají jen zřídka.

- Navrhované řešení:
    - Spolupráce několika farmaceutických firem (konsorcium), které chtějí vytvořit vlastní model na základě AlphaFold 3.
    - Použijí interní data, ale díky platformě od firmy Apheris mohou model trénovat, aniž by data musela opustit firemní servery.
    - Zatím nebude model veřejně dostupný – přístup budou mít jen členové konsorcia.

- Očekávání a další kroky:
    - Přesnost samotné predikce struktury se nejspíš výrazně nezlepší (ta je už teď výborná).
    - Velký potenciál je ale ve zlepšení predikce interakcí mezi proteiny a léčivy – což může výrazně urychlit vývoj léků.
    - Probíhá příprava na vyhodnocení modelu a veřejnou publikaci výsledků.
    - Někteří vědci a instituce usilují o vytvoření nové veřejné databáze s těmito daty.

- Sdílení dat:
    - Pouze 6 % záznamů v PDB pochází od farmaceutických firem.
    - Vědci volají po větší otevřenosti, ale firmy jsou zatím zdrženlivé.
