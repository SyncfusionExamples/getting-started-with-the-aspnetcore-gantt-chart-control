# ASP.NET Core Gantt Chart Example

A Razor Pages sample showing Syncfusion ASP.NET Core Gantt chart integration with hierarchical tasks, dependencies, and custom columns.

## Overview

This project demonstrates a Syncfusion Gantt chart in an ASP.NET Core Razor Pages application. It uses a local task data source with nested subtasks and configures a weekly timeline.

## Features

- Hierarchical tasks and subtasks
- Predecessor-based task dependencies
- Weekly timeline view
- Custom columns and task progress

## Prerequisites

- .NET 8 SDK
- Visual Studio 2022 or later
- Syncfusion ASP.NET Core license key

## Setup

1. Open `Program.cs`.
2. Replace `"Your License Key"` in `Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense(...)`.
3. Restore NuGet packages by rebuilding the solution.

## Run

1. Open `GanttExample.sln`.
2. Build and run.
3. View the chart on the home page.

## Implementation

- The `<ejs-gantt>` component is configured in `Pages/Index.cshtml`.
- The data source uses `GanttDataSource` objects and nested `SubTasks`.
- Dependencies use `Predecessor` and `dependency="Predecessor"`.
- Timeline mode is `Week`.

## Package

- `Syncfusion.EJ2.AspNet.Core` version `27.1.52`

## Notes

- A valid Syncfusion license key is required.

## References

- https://ej2.syncfusion.com/aspnetcore/documentation/gantt/getting-started
- https://ej2aspnetcore.azurewebsites.net/aspnetcore/gantt/overview#/bootstrap5
