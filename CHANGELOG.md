# Changelog
All notable changes to the Smart Recipe Ontology (SRO).
-----
## [0.1] - 2026-04-20
### Added
- Initial TBox with RecipeStep class
- Object properties: hasRecipeStep, usesIngredient, usesIngredientQuantity, referenceIngredient
- Data property: hasCaloriesPer100g
- Property chain axioms for ingredient inference
- Reused external Ontologies:
 - FoodON for food and recipe classes
 - QUDT for quantities and units
 - OWL Time for duration modeling
 - Schema.org for calorie properties
 - BFO for part-whole relations

### Example recipes
- Herb Omelette (3 steps, vegetarian)
- Pasta with Tomato Sauce (3 steps, vegan)
- Spaghetti with Tomato Sauce (4 steps, vegan)

----
## Future Plans
- Add cooking temperature modeling
- Add allergen information 
- Add serving size calculation 
- Add more recipe examples
- Multi-language support
