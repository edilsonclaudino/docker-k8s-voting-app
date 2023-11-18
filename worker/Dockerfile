FROM mcr.microsoft.com/dotnet/sdk:3.1 as builder
WORKDIR /Worker
COPY Worker.csproj .
RUN dotnet restore
COPY . .
RUN dotnet publish -c Release -o /out Worker.csproj

FROM mcr.microsoft.com/dotnet/aspnet:3.1
WORKDIR /app
COPY --from=builder /out .
ENTRYPOINT ["dotnet", "Worker.dll"]