FROM microsoft/aspnetcore:1.1
ARG source
WORKDIR /app
EXPOSE 80 
COPY ./WebApplication4/bin/Release/netcoreapp1.1/publish . 
ENTRYPOINT ["dotnet", "WebApplication4.dll"]