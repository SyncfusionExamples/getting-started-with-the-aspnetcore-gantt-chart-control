# ASP.NET Core Gantt Chart Example

A Razor Pages sample showing how to integrate the Syncfusion ASP.NET Core Gantt Chart with hierarchical tasks, dependencies, and configurable columns.

## Repository Description

This repository provides an ASP.NET Core example demonstrating how to configure and render the Syncfusion Gantt Chart using local task data with nested subtasks and scheduling relationships.

## Features

- Hierarchical tasks with parent and child relationships
- Predecessor‑based task dependency visualization
- Weekly timeline view configuration
- Custom column definitions for task information
- Task progress display using local data binding

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

- Getting started documentation: https://ej2.syncfusion.com/aspnetcore/documentation/gantt/getting-started
- Component overview: https://ej2.syncfusion.com/aspnetcore/gantt/overview#/bootstrap5
