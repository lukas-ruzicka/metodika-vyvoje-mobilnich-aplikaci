# Metodika vývoje mobilních aplikací

Tento repozitář slouží jako úložiště zdrojů pro mou diplomovou práci s názvem "Metodika vývoje mobilních aplikací" psanou na Fakultě Informatiky a Statistiky na Vysoké škole ekonomické v Praze pod vedením Ing. Václava Oškrdala, Ph.D. v roce 2020.

Finální verze celé práce je k dispozici [zde](Prace.pdf).

## Abstrakt

Předmětem této práce je vytvoření metodiky vývoje vhodné pro prostředí mobilních aplikací. Základu pro tvorbu metodiky je dosaženo pomocí analýzy specifik prostředí a existujících metodik. Na základě této analýzy je vybrána nejbližší metodika, která je dále upravena tak, aby vyhovovala specifikům prostředí.

Práce obsahuje také analýzu prostředí subjektu, který se zabývá vývojem mobilních aplikací a je vhodným kandidátem k osvojení navržené metodiky. Je tedy popsán možný přínos zavedení této metodiky a následně navržen i jeho postup, včetně návodu pro konfiguraci nástrojů pro podporu řízení.

Cílem této práce je vytvoření komplexní metodiky vývoje mobilních aplikací a navržení jejího jednoduchého zavedení a řízení v tomto prostředí.

Pokud se čtenář věnuje vývoji mobilních aplikací, přináší mu tato práce teoretický i praktický návod, jak řídit tento vývoj a může na základě získaných informací implementovat metodiku i ve vlastním prostředí.

## Zdroje práce

Níže se nachází digitální zdroje práce, které by měly ulehčit implementaci metodiky s použitím nástrojů popsaných v práci. Všechny zdroje jsou odkázány v praktické části práce a zde lze nalézt pouze návod na jejich použití.

### Jira

Ač nástroj Jira vyžadoval nejvíce různých konfigurací, jejich export byl možný pouze v dvou případech: workflow a automatizační pravidla.

#### Workflow

Všechna představená workflow lze nalézt [zde](Konfigurace/JiraWorkflows).

Bohužel, Jira `Cloud` verze poskytuje pouze možnost importu workflow z Atlassian obchodu. Pokud ovšem využíváte `Hosted` verze, je možné workflow importovat v `Administration` -> `Issues` -> `Workflows`, kde v pravém horním rohu kliknete na `Import` a vyberete možnost `Import workflow`.

#### Automatizační pravidla

Pravidla jsou k dispozici [v tomto souboru](Konfigurace/AutomatizacniPravidla/automation-rules-202011171500.json).

Automatizační pravidla jsou v tomto nástroji relativní novinkou a jsou také jedinou částí, kterou lze bez výjimek jednodušše exportovat a importovat. Stačí otevřít `Settings` -> `System` -> `Automation Rules`, vpravo nahoře kliknout na 3 tečky, vybrat `Import rules`, nahrát soubor `.json` a následně zaškrtnout všechna pravidla, která chcete importovat. Po potvrzení jsou pravidla nahrána a připravena k použití.

### Notion

Notion je nástroj pro tvorbu podnikové dokumentace. [Zde](http://htmlpreview.github.io/?https://github.com/lukysnupy/metodika-vyvoje-mobilnich-aplikaci/blob/main/Vzory/Projekt%20073bd6b74b554beeb50e95521757f58c.html) lze nalézt vzory pro dokumentace popsané v práci.

Bohužel, není možné vhodnou formou exportovat a importovat jednotlivé stránky při zachování struktury. Ovšem s použitím exportu ve formátu HTML je možné stránky zobrazit v prohlížeči, odkud je jejich obsah jednoduše možné zkopírovat. Zároveň je možné si stránky v prohlížeči "proklikat" a pochopit tak jejich strukturu.

---

Zpracoval a vytvořil Bc. Lukáš Růžička v roce 2020.
