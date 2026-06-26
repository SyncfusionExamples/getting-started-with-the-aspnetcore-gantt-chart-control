# ASP.NET Core Gantt Chart Example

A Razor Pages sample showing how to integrate the Syncfusion [ASP.NET Core Gantt Chart](https://www.syncfusion.com/aspnet-core-ui-controls/gantt-chart?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-gantt-chart-github-samples) with hierarchical tasks, dependencies, and configurable columns.

## Repository Description

This repository provides an ASP.NET Core example demonstrating how to configure and render the Syncfusion Gantt Chart using local task data with nested subtasks and scheduling relationships.

## Features

- Hierarchical tasks with parent and child relationships
- Predecessor‑based [task dependency](https://ej2.syncfusion.com/aspnetcore/documentation/gantt/task-dependency?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-gantt-chart-github-samples) visualization
- Weekly [timeline view](https://ej2.syncfusion.com/aspnetcore/documentation/gantt/time-line/time-line#timeline-view-modes?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-gantt-chart-github-samples) configuration
- Custom [column](https://ej2.syncfusion.com/aspnetcore/documentation/gantt/columns/columns?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-gantt-chart-github-samples) definitions for task information
- Task progress display using [local data binding](https://ej2.syncfusion.com/aspnetcore/documentation/gantt/data-binding#local-data?utm_source=github&utm_medium=listing&utm_campaign=aspnetcore-gantt-chart-github-samples)

## Prerequisites

- .NET SDK (8.0 or later)
- Visual Studio or a compatible ASP.NET Core development environment

## Getting Started

### Build and Run

1. Open the solution file in your development environment.
2. Restore NuGet packages.
3. Build and run the application.
4. Navigate to the home page to view the Gantt Chart.

## Implementation Details

- The Gantt Chart component is configured in `Pages/Index.cshtml`.
- Task data is defined using a local data model with nested `SubTasks`.
- Dependencies are mapped using the `Predecessor` field.
- The timeline is configured to display data in a weekly view.

## References

- [Explore ASP.NET Core Gantt Chart](https://www.syncfusion.com/aspnet-core-ui-controls/gantt-chart)
- [ASP.NET Core Gantt Chart Getting Started Guide](https://ej2.syncfusion.com/aspnetcore/documentation/gantt/getting-started)
- [ASP.NET Core Gantt Chart Live Demos](https://ej2.syncfusion.com/aspnetcore/gantt/default#/fluent2)
