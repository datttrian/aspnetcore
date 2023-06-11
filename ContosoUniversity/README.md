# Contoso University

``` bash
cd ContosoUniversity
dotnet tool restore
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run
```