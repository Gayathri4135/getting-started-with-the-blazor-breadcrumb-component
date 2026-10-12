# Getting Started with the Blazor Breadcrumb Component

## Overview

This sample demonstrates the Syncfusion [Blazor Breadcrumb](https://www.syncfusion.com/blazor-components/blazor-breadcrumb) component in a hosted Blazor WebAssembly application. The application showcases how to build hierarchical navigation paths using breadcrumb items, icons, URL based navigation, overflow handling, hidden item rendering, and custom templates. The sample provides a practical reference for implementing intuitive navigation experiences that help users understand their current location within an application's structure.

## Key Features

- Uses the `SfBreadcrumb` component from the `Syncfusion.Blazor.Navigations` namespace.
- Demonstrates hierarchical navigation using multiple `BreadcrumbItem` definitions.
- Configures breadcrumb items through the `Text` property to represent navigation paths.
- Uses the `Url` property to enable route based navigation.
- Demonstrates breadcrumb item icons using the `IconCss` property.
- Shows overflow handling through menu-style breadcrumb rendering.
- Demonstrates hidden-item behavior for compact layouts.
- Includes template customization for breadcrumb item rendering.
- Displays common navigation patterns used in dashboards, portals, and application hierarchies.
- Showcases responsive breadcrumb navigation scenarios in Blazor applications.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone the repository.
2. Open the `GettingStarted.sln` solution.
3. Restore all NuGet packages.
4. Ensure the appropriate startup project is selected for the hosted Blazor WebAssembly application.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the startup project directory for the hosted application.

```bash
dotnet restore
dotnet run
```

4. Open the application URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Solution file for the sample application.

- `Client/Pages/Index.razor` — Main page demonstrating breadcrumb navigation, icons, URL navigation, templates, menu mode, and hidden item handling.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/breadcrumb/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion