# Seznam povinností

Taky vždycky v pondělí zjišťujete, co všechno jste měli udělat do konce minulého týden a nestihli? S touhle aplikací si můžete jednoduše zapsat a odškrtat všechny povinnosti včas a bez problémů. 


## Funkční specifikace

### Datový konceptuální model (např. ER diagram či textový popis)
Uživatel bez přihlášení může ihned začít přidávat body seznamu a odškrtávat je. Pro uložení a sdílení seznamu je třeba se přihlásit (příp. registrovat). Po přihlášení je možné si nechat vypsat všechny seznamy povinností, které uživatel vytvořil.

### Charakteristika funkčností aplikace

 - Jednoduchá aplikace fungující i bez přihlášení
 - Bez přihlášení je možnost pouze lokální práce
 - Po přihlášení možnost uložení a sdílení seznamu

### Specifikace uživatelských rolí a oprávnění 

 - Návštěvník (bez přihlášení)
	 - Možnost upravovat 1 seznam, po zavření prohlížeče seznam zmizí
	 - Možnost otevření seznamu, který vytvořil jiný uživatel
 - Přihlášený uživatel
	 - Vše jako návštěvník
	 - Navíc možnost uložení seznamu
	 - Možnost sdílení kopírovacího odkazu na seznam (po použití se otevře jako předvyplněný seznam, ale změny se neprojevují v původním seznamu, pokud je tento otevřen jiným uživatelem)

### Uživatelské grafické rozhraní a jeho funkčnosti
Grafické rozhraní bude vzdušné a jednoduché, aby byly seznamy přehledné a dobře se v nich orientovalo. Po přihlášení bude možnost přepnutí pohledu na 



## Technická specifikace

### Datový logický model

### Popis architektury a jejích jednotlivých částí.

#### Popis tříd včetně základních funkcí, které by měly dané třídy plnit

#### Použité technologie a funkčnosti jednotlivých částí aplikace (např. html stránek, sekcí aplikace z pohledu uživatele apod.)
