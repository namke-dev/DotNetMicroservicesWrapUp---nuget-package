install package
```powershell
dotnet add package Microsoft.Extensions.Configuration
dotnet add package Microsoft.DependencyInjection
dotnet add Microsoft.Extensions.Configuration.Binder
```

Add nuget packate to enable async cummunication by using publishing message via MassTransit
```powershell
dotnet add package MassTransit.AspNetCore
dotnet add package MassTransit.RabbitMQ
```


Packing
```powershell
dotnet pack -o <Dir to store source>
dotnet nuget add source <Dir to stored source>
```