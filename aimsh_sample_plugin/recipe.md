---
description: Generate a recipe for the given dish
expects:
  dish: Dish to create recipe for
response:
  title: Title of the recipe
  ingredients: The ingredients for the recipe (as a string)
  instructions: The instructions to prepare the recipe (as a string)
---
Please create a recipe for {{dish}}.
Respond with the recipe title, the ingredients, and the steps to prepare it.