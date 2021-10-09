Our recipes are now more complicated and we have to know the quantity of each item to know if we can cook it. Our `fridge` now contains an association between each item and how many of it we have (you may know this as map, dictionary, object or table). Similarly, `ingredients` contains an association of each item and how many of it are required to make the meal.

We should write a function once again that takes these two variables and return `true` or `false` based on whether we can make the given recipe.

#### Example 1 (should return `false`):
```
ingredients = {'tomato': 1, 'onion': 2};
fridge = {'tomato': 1, 'onion': 1};
```

#### Example 2 (should return `true`):
```
ingredients = {'tomato': 2, 'onion': 3};
fridge = {'tomato': 2, 'onion': 3, 'olives': 1};
```

```
function validateRecipe(fridge, ingredients) {
  // complete this function
}
```
