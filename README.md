# BasicZahooApp

A basic .NET core console application that uses Yahoo! oauth provider.

Had to name it as BasicZahooApp instead of BasicYahooApp
because when registering application name it refuses to accept application names with `Yahoo`

```ps1: In C:\src\github.com\ongzhixian\BasicZahooApp
dotnet new sln -n BasicZahooApp
dotnet new console -n BasicZahooApp.ConsoleApp
dotnet sln .\BasicZahooApp.sln add .\BasicZahooApp.ConsoleApp\


dotnet user-secrets --project .\BasicZahooApp.ConsoleApp\ init
dotnet user-secrets --project .\BasicZahooApp.ConsoleApp\ set "<some-key>" "<some-value>"

```