We are building an application that helps chefs determine if they're able to cook a certain recipe. For a recipe to be possible, the chef must have all its ingredients available in the fridge.

Write a function that takes two arrays, one is a `fridge` and one is a `ingredients`.
The `fridge` is an array of all items you have available in your fridge.
The `ingredients` is an array of items you need to be able to cook a certain meal.
Your function should return `true` if the chef is able to cook the given meal.

#### Example 1 (should return `false`):
```
ingredients = ['tomato', 'onion', 'lettuce']
fridge = ['tomato', banana', 'apple', 'onion', 'cucumber']
```


#### Example 2 (should return `true`):
```
ingredients = ['olives', 'onion', 'lettuce']
fridge = ['onion', banana', 'lettuce', 'olives']
```

```
function validateRecipe(fridge, ingredients) {
  // complete this function
}
```
