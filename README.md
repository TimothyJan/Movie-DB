# RazorPagesMovie
Movie Database using Razor Pages web app with ASP.NET Core

<br>

Tutorial: Create a Razor Pages web app with ASP.NET Core <a href="https://learn.microsoft.com/en-us/aspnet/core/tutorials/razor-pages/?view=aspnetcore-8.0">link</a>

<br>

Entity Framework Core (EF Core)
<ul>
  <li>The app's model classes use Entity Framework Core (EF Core) to work with the database.</li>
  <li>EF Core is an object-relational mapper (O/RM) that simplifies data access.</li>
  <li>You write the model classes first, and EF Core creates the database.</li>
</ul>

Scaffold the movie model
<ul>
  <li>After creating the data model by adding the necessary properties to the class.</li>
  <li>The scaffolding tool produces pages for Create, Read, Update, and Delete (CRUD) operations for the model.</li>
</ul>

The migrations feature in Entity Framework Core provides a way to:
<ul>
  <li>Create the initial database schema.</li>
  <li>Incrementally update the database schema to keep it in sync with the app's data model. Existing data in the database is preserved.</li>
</ul>

