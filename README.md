# How to Create and Customize Blazor Financial Charts

## Overview

This sample demonstrates how to create and customize financial charts using the Syncfusion Blazor Chart component. The application focuses on financial data visualization scenarios and showcases the High-Low (Hilo), Open-High-Low-Close (OHLC), and Candle chart types used to represent stock market price movements and trading activity.

The sample illustrates how financial data consisting of open, high, low, close, and volume values can be visualized through specialized chart series. It provides a practical reference for implementing stock-market style charting experiences in Blazor applications using Syncfusion chart components.

## Key Features

- Demonstrates Syncfusion Blazor financial chart types.
- Renders High-Low (Hilo) chart series for displaying high and low stock values.
- Renders Open-High-Low-Close (OHLC) chart series to represent opening, closing, highest, and lowest trading values.
- Renders Candle chart series for visualizing stock price movement through candlestick representations.
- Uses financial datasets containing open, high, low, close, and volume information.
- Demonstrates chart customization and financial data presentation using built-in Syncfusion chart capabilities.
- Provides examples of stock-market oriented data visualization in a Blazor application.
- Uses a dedicated Blazor application project (`FinancialCharts.csproj`) to host the financial chart examples.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `FinancialCharts.sln`.
3. Restore all NuGet packages.
4. Set the `FinancialCharts` project as the startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root containing `FinancialCharts.csproj`.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/` — contains the Blazor pages that render the Syncfusion financial chart examples.
- Additional files within the Pages and Data folders support the implementation of Hilo, OHLC, and Candle chart visualizations.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to this feature, see https://help.syncfusion.com/chart-sdk/blazor/charts/chart-types/high-low

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.