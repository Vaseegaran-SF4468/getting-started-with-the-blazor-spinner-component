# Getting Started with the Blazor Spinner Component

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Spinner](https://www.syncfusion.com/blazor-components/blazor-spinner?utm_source=github&utm_medium=listing&utm_campaign=blazor-spinner-github-samples) component in a hosted Blazor WebAssembly application. The application shows how to display loading indicators while asynchronous or long-running operations are in progress so users receive immediate visual feedback. The sample also demonstrates controlling Spinner visibility and applying common appearance customizations used in real-world applications. It serves as a practical starting point for integrating loading experiences into Syncfusion Blazor applications.

## Key Features

- Renders multiple Syncfusion Blazor Spinner components using different spinner types, including the default Bootstrap5 style and `SpinnerType.Bootstrap`.
- Uses the `Visible` property to control Spinner display during application execution.
- Demonstrates two-way binding with `@bind-Visible` for dynamic Spinner visibility management.
- Displays descriptive loading text using the `Label` property.
- Customizes Spinner appearance through the `CssClass` property and custom CSS styling.
- Applies custom Spinner color styling by targeting the Bootstrap5 Spinner SVG stroke.
- Integrates Spinner functionality with the Syncfusion Tab component.
- Uses the `Selecting` event to display a loading indicator while tab content is being switched.
- Uses the `Selected` event to hide the loading indicator after tab navigation completes.
- Demonstrates asynchronous loading behavior using `Task.Delay()` to simulate background processing.
- Shows an alternative implementation approach using Spinner instance methods (`ShowAsync()` and `HideAsync()`) through component references.
- Demonstrates overlay-style loading indicators using custom CSS classes and Spinner layering.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `GettingStarted.sln` solution file.
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

- `GettingStarted.sln` — Visual Studio solution file containing the sample projects.
- `Client/Pages/Index.razor` — Main sample page demonstrating Spinner types, custom styling, labels, visibility binding, and integration with Tab events.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official Spinner documentation: https://blazor.syncfusion.com/documentation/spinner/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.