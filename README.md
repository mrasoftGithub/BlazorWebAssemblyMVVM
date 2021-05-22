# BlazorWebAssemblyMVVM
Voorbeeldcode horend bij de Blog artikelen https://www.mrasoft.nl/blazor-webassembly-MVVM/ en https://www.mrasoft.nl/blazor-binding/

Hier staat een ASP .NET Core hosted Blazor WebAssembly App. Voor de solution is de Visual Studio 2019 IDE gebruikt. Het gebruikte .Net Framework is .Net 5.0.

De voorbeeldcode bevat een implementatie die gebruik maakt van een SQL Server database. De SQL Server database zit niet in deze GitHub respository. Maak hiervoor op je SQL Server een database aan met de naam **VOORBEELD** en creëer in die database een tabel met de naam **EIGENAAR**. Neem de volgende velden op in de tabel:
- ID (int, not null, primary key - Identity Specification, Identity increment: 1, Identity Seed: 1)
- omschrijving (nvarchar(MAX) - Allow Nulls)
- voornaam (nvarchar(50) - Allow Nulls)
- achternaam (nvarchar(50) - Allow Nulls)
- regio (nvarchar(50) - Allow Nulls)

Pas ten slotte de connectiestring aan in configuratiebestand **appsettings.json** in je .server project.

Lees ook mijn [blog](https://www.mrasoft.nl) over C# en Blazor.
