# Dont et Baby 💋
Dot Net Commands for MacOS that I use but often forget

## Backend references for MacOS - 
You're basically working with Entity Framework so you have to add (4) Entity Framework Packages with Nuget Packet Manager

- EntityFramework Core



#### Web Api with ASP.net and Entity Framework
- [Tutorial: Create a web API with ASP.NET Core](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-7.0&tabs=visual-studio)
- [Dockerize your SQL Server and use it in ASP.NET Core with Entity Framework Core](https://www.twilio.com/blog/containerize-your-sql-server-with-docker-and-aspnet-core-with-ef-core)
- [How to containerize your ASP.NET Core application and SQL Server with Docker](https://www.twilio.com/blog/containerize-your-aspdotnet-core-application-and-sql-server-with-docker)
- [Working with Primary and Foreign Keys](https://learn.microsoft.com/en-us/ef/core/modeling/keys?tabs=data-annotations)


#### Scaffolding

Run the below command

> dotnet-aspnet-codegenerator controller -name GoodsInTransitCertController -async -api -m GoodsInTransitCert -dc GoodsInTransitContext -outDir Controllers


#### To add dotnet ef to CLI 
- dotnet tool install --global dotnet-ef

#### To create migration
- dotnet ef migrations add InitialCreate

#### To run migration
- dotnet ef database update
