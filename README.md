## Create sln dotnet new cmd

```
dotnet new sln -n mysolution
dotnet new console -o myapp
dotnet new classlib -o mylib1
dotnet new classlib -o mylib2
dotnet sln mysolution.sln add myapp\myapp.csproj
dotnet sln mysolution.sln add mylib1\mylib1.csproj --solution-folder mylibs
dotnet sln mysolution.sln add mylib2\mylib2.csproj --solution-folder mylibs

```


