# How to Load a Web Page Inside Blazor Tab Component?

## Project Overview
The purpose of this project is to help developers understand how to integrate web content within the Syncfusion [Blazor Tabs](https://www.syncfusion.com/blazor-components/blazor-tabs) component. It provides a reference implementation for rendering external web pages inside tab panels, which is useful for dashboards, documentation views, or embedded tools.

## Features
- Integration of the Syncfusion Blazor Tabs component  
- Load and display external web pages inside tab content  
- Tab‑based navigation for organizing multiple views  
- Simple and reusable Blazor tab implementation  

## Prerequisites
Ensure the following requirements are met before running this project:
- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with Blazor  

## Installation and Running the Project
**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `LoadingWebsite.sln`

3. Restore the NuGet packages by rebuilding the solution.
4. Set the startup project to:

   `LoadingWebsite`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Open the application URL displayed by Visual Studio after launch.
8. Select each tab and verify that the web page configured for that tab is loaded and displayed correctly inside the Tab component.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory:

```bash
cd how-to-load-website-inside-blazor-tab-component
```

5. Restore the NuGet packages:

```bash
dotnet restore
```

6. Run the project:

```bash
dotnet run
```

7. Open the local URL displayed in the terminal after the application starts.
8. Select each tab and verify that the web page configured for that tab is loaded and displayed correctly inside the Tab component.

## Usage
Run the application and navigate through the tabs to see how an external web page is rendered within a tab panel. This approach can be extended to embed documentation pages, dashboards, or internal web tools inside Blazor applications.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Tabs getting started documentation](https://blazor.syncfusion.com/documentation/tabs/getting-started)

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.