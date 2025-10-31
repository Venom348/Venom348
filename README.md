<div id="header" align="center">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExbXhybXFqOGY4bzA5aG94b2Q1a3pudjl2MHk2c29zcHg3NmthOTdtaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/78XCFBGOlS6keY1Bil/giphy.gif" width="120"/>
</div>

```csharp
var developer = new
{
    Pronouns = new[] { "He", "Him" },
    Code = new[] { "C#", ".NET", "SQL"},
    AskMeAbout = new[] { "backend dev", "Web API development", "microservices" },
    Technologies = new
    {
        BackEnd = new
        {
            DotNet = new[] { ".NET 8", ".NET 9", ".NET Core", "ASP.NET Core", },
            Frameworks = new[] { "Entity Framework Core", "Dapper", "MediatR", "AutoMapper" },
            Patterns = new[] { "CQRS", "Clean Architecture", "Repository Pattern", "DDD" }
        },
        DevOps = new[] { "Docker🐳", "Kubernetes", "CI/CD" },
        Databases = new[] { "PostgreSQL", "Redis" },
        Misc = new[] { "REST APIs","RabbitMQ", "Swagger/OpenAPI" },
        Testing = new[] { "xUnit" },
        Tools = new[] {"JetBrains Rider", "Postman" }
    },
    Architecture = new
    {
        Patterns = new[] { "Microservices", "Clean Architecture", "Domain-Driven Design", "CQRS" },
        Messaging = new[] { "RabbitMQ" },
        Caching = new[] { "Redis" }
    },
    CurrentFocus = "Building scalable microservices with .NET",
    FunFact = "I like to stay at home and play computer games"
};
```

