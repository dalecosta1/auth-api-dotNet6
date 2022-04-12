# .Net core 6 auth-api with swagger and refresh token

This is an example of back-end api for authentication using .Net core 6 

## Installation .Net ef-tools

First, installing the .Net ef-tool

```bash
dotnet tool install -g dotnet-ef
```
Or updating it
```bash
dotnet tool update -g dotnet-ef
```

For more info on EF Core tools see 
[https://docs.microsoft.com/ef/core/cli/dotnet](https://docs.microsoft.com/ef/core/cli/dotnet).

For more info on EF Core migrations see 
[https://docs.microsoft.com/ef/core/managing-schemas/migrations](https://docs.microsoft.com/ef/core/managing-schemas/migrations).


## Usage
Configure SMTP settings for email within the AppSettings section in the /appsettings.json file. 
For quick testing you can create a temporary inbox at https://ethereal.email/ and copy the SMTP configuration options.

Start the API by running: 
```bash
dotnet run 
```

from the command line in the project root folder (where the WebApi.csproj file is located), you should see the message Now listening on: http://localhost:4000, and you can view the Swagger API documentation at http://localhost:4000/swagger.

## Contributing
@dalecosta1

## License
[MIT](https://choosealicense.com/licenses/mit/)