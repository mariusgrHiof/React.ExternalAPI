# React.ExternalAPI

This is a website to view JDM cars. Each car has a picture, make, model, year of release and description.
The api is build with asp.net web api and the database runs on Sql server. The frontend is built with React and using Material UI.

# Installation
git clone https://github.com/mariusgrHiof/React.ExternalAPI.git
cd React.ExternalAPI

# To run the api
cd API/ExternalAPI
Make sure to add the corret connectionstring in the appsettings.Development.json.
Run: dotnet ef database update
Rune: dotnet run

# To run the frontend
cd into React.ExternalAPI/Frontend/client
Run: npm install
Run: npm start
