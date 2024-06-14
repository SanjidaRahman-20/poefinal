Recipe Manager Application
The Recipe Manager Application is a simple tool designed to manage recipes, allowing users to add, remove, display, filter, and scale recipes. It provides a graphical user interface (GUI) built using WPF (Windows Presentation Foundation) and C#.

Features
Add Recipe: Users can add new recipes with ingredients and preparation steps.
Remove Recipe: Recipes can be removed from the manager.
Display Recipe: Details of a selected recipe can be viewed.
Scale Recipe: Quantities of ingredients in a recipe can be scaled by a specified factor.
Filter Recipes: Recipes can be filtered based on ingredient, food group, and maximum calorie content.
Notification: Warns users when a recipe's total calories exceed 300.
Prerequisites
.NET Framework or .NET Core installed on your machine.
Visual Studio or another compatible IDE for C# development.
Getting Started
Clone the repository or download the source code.
Open the solution in Visual Studio.
Build and run the RecipeManagerApp project.
Usage
Adding a Recipe: Enter a recipe name, add ingredients with quantities, units, calories, and food groups, then add preparation steps.
Removing a Recipe: Select a recipe from the list and click "Remove Recipe".
Displaying a Recipe: Select a recipe from the list and click "Display Recipe" to view its details.
Scaling a Recipe: Select a recipe from the list, enter a scale factor in the "Scale Recipe" section, and click "Scale Recipe".
Filtering Recipes: Enter an ingredient name, select a food group, specify a maximum calorie limit, and click "Apply Filter" to display filtered recipes.
Notifications: When adding a recipe, a notification will appear if the total calories exceed 300.
Structure
MainWindow.xaml: XAML file defining the application's main window layout.
MainWindow.xaml.cs: Code-behind file containing C# logic for event handling and business logic.
Recipe.cs: Class file defining the Recipe class with properties and methods for managing recipes.
RecipeManager.cs: Class file defining the RecipeManager class responsible for managing a collection of recipes.
