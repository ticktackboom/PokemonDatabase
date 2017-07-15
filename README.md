# The Pokemon Database

* MySQL Database: Complete Pokémon database of all 721 Pokémon (Generation from I to VI)
* JSON Database: Complete Pokémon database of 151 Pokémon (Generation I). Data dumped directly from original ROM games.

# Ejemplos

Lista de todos los pokémon junto a su número ID nacional:

```sql
SELECT pokemon_species_id, name FROM `pokemon_species_names` WHERE local_language_id = 7;
```

