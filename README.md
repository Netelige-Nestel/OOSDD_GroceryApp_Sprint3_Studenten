## Gitflow Documentatie

Onze branching strategie maakt gebruik van meerdere branches.

Main:

- De main branch bewaart de hoofdversies van de repository.
- Alle aanpassingen aan de main branch moeten met een pull request worden goedgekeurd.
- Releases worden altijd vanaf de main branch gemaakt.

Development:

- Vanaf development worden feature branches gemaakt.

Feature:

- Nieuwe functionaliteiten worden vanaf feature branches gemaakt.
- Feature branches mergen met Development, niet met main.
- Feature branches worden na gebruik verwijderd.

Hotfix:
	
- Hotfix branches worden vanaf main gemaakt.
- Gebruik hotfix branches voor snelle bugfixes aan main.
- Hotfix branches worden na gebruik verwijderd.


# GroceryApp sprint3 Studentversie  
    
## UC07 Delen boodschappenlijst  
Is compleet  
  
## UC08 Zoeken producten  
Aanvullen:
- In de GroceryListItemsView zitten twee Collection Views, namelijk één voor de inhoud van de boodschappenlijst en één voor producten die je toe kunt voegen aan de boodschappenlijst  
- Voeg boven de tweede CollectionView een zoekveld (SearchBar) in om op producten te kunnen zoeken.  
- Zorg dat de SearchCommand wordt gebonden aan een functie in het onderliggende ViewModel (GroceryListItemsViewModel) en dat de zoekterm die in het zoekveld is ingetypt gebruikt wordt als parameter (SearchCommandParameter).  
- Werk in het viewModel (GroceryListItemsViewModel) de zoekfunctie uit en zorg dat de beschikbare producten worden gefilterd op de zoekterm!  

## UCx Registratie gebruiker 
Of een ander idee zelf uitwerken. Dit betekent ook dat de documentatie hiervoor ontwikkeld moet worden.

  

