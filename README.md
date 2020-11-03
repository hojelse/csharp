# csharp

Project Setup
```
dotnet new sln -o unit-testing-using-dotnet-test
cd unit-testing-using-dotnet-test
dotnet new console -o MyProject
ren .\MyProject\Program.cs MyProject.cs
dotnet sln add ./MyProject/MyProject.csproj
dotnet new xunit -o MyProject.Tests
dotnet add ./MyProject.Tests/MyProject.Tests.csproj reference ./MyProject/MyProject.csproj
dotnet sln add ./MyProject.Tests/MyProject.Tests.csproj
```

## Development

From project dir
```
dotnet run
```

From test dir
```
dotnet test
```
