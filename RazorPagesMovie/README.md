# Razor Pages Movie

``` bash
git clone https://github.com/datttrian/aspnetcore && cd aspnetcore
cd RazorPagesMovie
dotnet tool restore
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run
```