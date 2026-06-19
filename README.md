# UKParliamentEndPointsAdmin

A .NET 8 Blazor WebAssembly admin application for managing the UK Parliament endpoints dataset.

This repository contains the admin UI. The companion API and shared data model live in [ChrisBrooksbank/UKParliamentEndpoints](https://github.com/ChrisBrooksbank/UKParliamentEndpoints).

## Project structure

- `UKParliamentEndPointsAdmin/` - ASP.NET Core host for the Blazor WebAssembly app.
- `UKParliamentEndPointsAdmin.Client/` - Blazor WebAssembly client.
- `UKParliamentEndPointsAdmin.sln` - Visual Studio solution.

## Prerequisites

- .NET 8 SDK

## Run locally

```bash
dotnet restore
dotnet run --project UKParliamentEndPointsAdmin/UKParliamentEndPointsAdmin.csproj
```

The app uses the standard ASP.NET Core local launch settings when run from Visual Studio or `dotnet run`.

## Related repositories

- [UKParliamentEndpoints](https://github.com/ChrisBrooksbank/UKParliamentEndpoints) - API and Azure Table storage integration.
- [UKParlyEndPointsFuncApp](https://github.com/ChrisBrooksbank/UKParlyEndPointsFuncApp) - scheduled Azure Functions for endpoint checks.
- [UKParliamentEndPointsAIChat](https://github.com/ChrisBrooksbank/UKParliamentEndPointsAIChat) - AI chat interface over the endpoint data.
