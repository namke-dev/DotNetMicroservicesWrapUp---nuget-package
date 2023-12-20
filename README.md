install package
```powershell
dotnet add package Microsoft.Extensions.Configuration
dotnet add package Microsoft.DependencyInjection
dotnet add Microsoft.Extensions.Configuration.Binder
```

Packing
```powershell
dotnet pack -o <Dir to store source>
dotnet nuget add source <Dir to stored source>
```