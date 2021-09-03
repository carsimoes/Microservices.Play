# Microservices.Play

dotnet --info
C# extensions vscode

docker run -d --rm --name mongo -p 27017:27017 -v mongodbdata:/data/db mongo

dotnet pack -o ..\..\..\packages\
dotnet nuget add source C:\Git\Microservices.Play\packages -n PlayEconomy

dotnet add package Play.Commond

docker ps
docker stop mongo

docker compose up

dotnet new webapi -n Play.Inventory.Service
dotnet add package Play.Common

rabbitmq
user:guest
password:guest
