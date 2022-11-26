# Seznamy povinností

Taky vždycky v pondělí zjišťujete, co všechno jste měli udělat do konce minulého týden a nestihli? S touhle aplikací si můžete jednoduše zapsat a odškrtat všechny povinnosti včas a bez problémů. 


## Funkční specifikace

### Datový konceptuální model (např. ER diagram či textový popis)
Uživatel bez přihlášení může ihned začít přidávat body seznamu a odškrtávat je. Pro uložení seznamu se využije local storage.

### Charakteristika funkčností aplikace

 - Jednoduchá aplikace fungující bez přihlášení

### Specifikace uživatelských rolí a oprávnění 

 - Návštěvník (bez přihlášení)
	 - Možnost upravovat 1 seznam, po zavření prohlížeče seznam nezmizí, je nadále uložen v local storage. Zmizí až se smazáním local storage daného webu.

### Uživatelské grafické rozhraní a jeho funkčnosti
Grafické rozhraní bude vzdušné a jednoduché, aby byl seznam přehledný a dobře se v něm orientovalo. 

## Technická specifikace

### Datový logický model
Při uložení dojde k uložení jednotlivých úkolů do tabulky todos, a jejich doplnění o id a informaci o splnění.

### Popis architektury a jejích jednotlivých částí.
Základem bude čistý JavaScript bez dalších knihoven, který zajistí nejen vytvoření konkrétního úkolu, ale i jeho uložení.

#### Popis tříd včetně základních funkcí, které by měly dané třídy plnit
Projekt bude vytvořen podle MVC architektury.
- Model zajišťuje vlastnosti všech úkolů
- View obhospodařuje, kdy a za jakých podmínek se mají které úkoly zobrazit 
- Controller obsahuje hlavní funkce (přidání, zaškrtnutí, uložení, odebrání úkolu)


#### Použité technologie a funkčnosti jednotlivých částí aplikace (např. html stránek, sekcí aplikace z pohledu uživatele apod.)
Pokusím se použít pouze JavaScript v jeho objektové podobě, bez dalších frameworků. 
