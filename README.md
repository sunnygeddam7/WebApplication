# ASP.NET Core CICD pipeline Sample using Jenkins

## 'Restore packages' : - 'dotnet restore WebApplication.sln'
## 'Clean' : - 'dotnet clean WebApplication.sln --configuration Release'
## 'Build' : - 'dotnet build WebApplication.sln --configuration Release --no-restore'
## 'Test: Unit Test' : - 'dotnet test XUnitTestProject/XUnitTestProject.csproj --configuration Release --no-restore'
## 'Publish' : - 'dotnet publish WebApplication/WebApplication.csproj --configuration Release --no-restore'