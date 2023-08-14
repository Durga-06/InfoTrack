# WebScrapper for InfoTrack technical test

open the solution file in a visual studio - WebScrapper.Sln

## Api Setup
for the db setup, please execute following:
using the Visual Studio console, go to WebScrapper.Data and execute command "dotnet ef databse update"

## Spa Setup
To run the UI app:
using command prompt/VS code terminal/visual studio console, go to ClientApp and execute first "npm i" to install all the project dependencies and then "npm run ng serve"

## Design
The app is running on .NET 7

This is an N Tier Web API solution that has been splitted into 4 layers - API + Application + Core + Data
The architecture includes Depenency injection (DotNet.Core), Mediator pattern which is a probably a little too much for such a small app but I've just tried to demonstrate my knowledge
Swagger is included so the API can be tested on https://localhost:7045/swagger

The Single Page Application is implemented using latest Angular and Bootstrap


============================= SCREENSHOTs ===================

Homepage/Dashboard

Google Search
![image](https://user-images.githubusercontent.com/1809650/159509906-3ed4c7a7-a90c-4f53-8228-9d5ad69d679a.png)

Bing Search
![image](https://user-images.githubusercontent.com/1809650/159510621-24e8a44b-78d0-45d8-8d9b-d8ba7344e9fe.png)

SEARCH-HISTORY
![image](https://user-images.githubusercontent.com/1809650/159510298-1053fb62-c860-4b2e-913a-ebfc13f33abd.png)

