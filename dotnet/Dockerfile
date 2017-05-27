FROM microsoft/aspnetcore-build:1.1.2-jessie

COPY . /app
WORKDIR /app
RUN ["dotnet", "restore"]
RUN ["dotnet", "build"]

EXPOSE 80/tcp
ENTRYPOINT ["dotnet", "run"]