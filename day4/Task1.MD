# Практика Kotlin fundamentals. День 4
## Практика 1

1. У вас есть класс Student с полями: name (имя), course (курс) и grades (оценки типа Map<String, Integer>). Также у вас есть класс University с полями: subjects (список предметов) и students (список студентов).
Вам необходимо в классе University реализовать следующие методы:

`printStudentByCourse(course: Int):Unit` - этот метод должен выводить на экран информацию о студентах, которые учатся на определенном курсе.
`transferStudent():Unit` - данный метод должен переводить студентов на следующий курс, если их средний балл выше 3.
`deleteStudents():Unit` - этот метод должен исключать из списка студентов тех, у кого средний балл ниже 3.

2. У вас есть класс Recipe (Рецепт) с полями:
String name (название рецепта)
List<String> ingredients (список ингредиентов)
String instructions (инструкции по приготовлению)
Также у вас есть класс Cookbook (Книга рецептов) с полями:
List<Recipe> recipes (список рецептов)
Задача:
В классе Cookbook (Книга рецептов) реализуйте следующие методы:
fun addRecipe(recipe: Recipe) - добавить новый рецепт в книгу рецептов.
fun findRecipesByIngredient(ingredient: String): List<Recipe> - найти все рецепты, которые содержат определенный ингредиент.
fun printAllRecipes() - напечатать все рецепты из книги рецептов.
