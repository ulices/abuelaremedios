== README ==

# ABUELA REMEDIOS

## Home Medicine

### Mdoel Structure

```
Models
  User
    name
    email

  Roles
    name

  UserRoles
    user_id
    role_id

  Recipes
    name
    description
    state
    how_to_use
    how_to_create

  Ingredients
    name
    description

  RecipesIngredients
    recipe_id
    ingredient_id

  Tags
    name

  RecipesTags
    recipe_id
    tag_id

  Ranking
    recipe_id
    user_id
    value

  Comments
    description
    recipe_id
    user_id
```
