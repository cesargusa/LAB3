
FROM mcr.microsoft.com/dotnet/core/aspnet:3.1

 COPY bin/Release/netcoreapp3.1/publish/ TestWebAPI/
 WORKDIR /TestWebAPI
 ENTRYPOINT ["dotnet", "TestWebAPI.dll"]