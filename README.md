# .NET 7 Hello World

This sample demonstrates a tiny Hello World .NET Core app for [App Service Web App](https://docs.microsoft.com/azure/app-service-web). This sample can be used in a .NET Azure App Service app as well as in a Custom Container Azure App Service app.

# Build your DotNetCore application

`cd DotNetCoreHelloWorld`
`dotnet publish -c Release - ./myapp`

# Run DotNetCore application from the published build

`cd ./myapp/`
`dotnet dotnetcoresample.dll`
