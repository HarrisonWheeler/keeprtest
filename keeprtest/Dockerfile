FROM mcr.microsoft.com/dotnet/sdk:5.0
COPY ./bin/Release/dotnet3.5/publish/ App/
WORKDIR /App
CMD ASPNETCORE_URLS=http://*:$PORT dotnet keeprtest.dll
