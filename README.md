<div align="center">

[![Language][language-shield]][language-url]
[![Language][languageH-shield]][languageH-url]
[![Language][languageC-shield]][languageC-url]
[![MIT License][license-shield]][license-url]

## Recipe Box

#### This is a C# web application using authentication that stores recipes based on tags!

<br>

#### _By Paige Tiedeman & Anna Clarke_

<br>
 
</div>

## Technologies Used

* C#
* .NET v5.0
* ASP.NET Core MVC
* HTML 
* Bootstrap
* MySQL
* CSS
* MySQL Workbench
* Razor
* Entity FrameworkCore
* .NET Core CLI

## Description

This web application lets the user add recipes and tags only after they have created and logged in, the user can connect recipes to tags. The users recipes are displayed in highest rated order and are searchable by ingredients.

## Installation Requirements

* _Clone or download the zip file of this repository to your desktop_
* _Navigate into the top level directory_
* _Open in your code editor_
* _Commit and push your .gitignore file to your repo_
* _Add the file RecipeBox.Solution/RecipeBox/appsettings.json and insert the following:_
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=recipe_box;uid=[YOUR-UID];pwd=[YOUR-PASSWORD-HERE];"
  }
}
```
* _Insert your MySQL password and user Id_
* _Make sure to have .NET 5.0 installed_
* _Run `$ dotnet restore` to install bin & obj folders_
* _Make sure to have EntityFrameworkCore.Design 5.0 added and dotnet ef installed globally_


## Steps To Use
* _In your terminal navigate into RecipeBox.Solution/RecipeBox_
* _If Migrations folder is not present run `$ dotnet ef migrations add Initial` to add Migrations folder_
* _Then run `$ dotnet ef database update` to create the schema_
* _Run `$ dotnet build` to build the site_
* _Run `$ dotnet run` to start the live server_
* _On the home page, click 'Create an Account', and follow the steps to register as a new user_
* _Click either button to see all recipes or tags_
* _After clicking add  put in your inputs and hit submit to reveal the lists!_
* _There is also a search button to search by Ingredients_

## User Stories

<details>
<summary> As A User..</summary>

* I want to add a recipe with ingredients and instructions, so I remember how to prepare my favorite dishes.
* I want to tag my recipes with different tags, so recipes are easier to find. A recipe can have many tags and a tag can have many recipes.
* I want to be able to update and delete tags, so I can have flexibility with how I categorize recipes.
* I want to edit my recipes, so I can make improvements or corrections to my recipes.
* I want to be able to delete recipes I don't like or use, so I don't have to see them as choices.
* I want to rate my recipes, so I know which ones are the best.
* I want to list my recipes by highest rated so I can see which ones I like the best.
* I want to see all recipes that use a certain ingredient, so I can more easily find recipes for the ingredients I have.
* I want to create an account.
* I want to be able to log in and log off.
* I want to be able to see my account details.

</details>

## Known Bugs

* _N/A_

## License

MIT: See Badge at top for Info
Copyright (c) 2021 Paige Tiedeman and Anna Clarke

## Contact Information

_Paige Tiedeman @ github.com/paigetiedeman_  
_Anna Clarke @ anclarkie@gmail.com_

[license-shield]: https://img.shields.io/badge/License-MIT-blue
[license-url]: https://opensource.org/licenses/MIT
[language-shield]: https://img.shields.io/badge/Language-C%23-green
[language-url]: https://docs.microsoft.com/en-us/dotnet/csharp/
[LanguageH-shield]: https://img.shields.io/badge/Language-HTML-red
[LanguageH-url]: https://developer.mozilla.org/en-US/docs/Web/HTML
[LanguageC-shield]: https://img.shields.io/badge/Language-CSS-blueviolet
[LanguageC-url]: https://developer.mozilla.org/en-US/docs/Web/CSS