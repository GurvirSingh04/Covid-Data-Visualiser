# Covid Data Visualiser

This repository contains a Java-based application designed to visualise COVID-19 data. The application provides graphical representations of COVID-19 statistics, allowing users to analyse trends and patterns effectively.

## Features

- **Data Visualisation**: Graphical representation of COVID-19 statistics.
- **Interactive Charts**: Users can interact with charts to view specific data points.
- **Map Integration**: Visualise data on a borough map for geographical analysis.
- **Statistical Analysis**: Calculate and display key statistics related to COVID-19 data.

## Prerequisites

- Java Development Kit (JDK) installed on your system.
- An Integrated Development Environment (IDE) like IntelliJ IDEA or Eclipse (optional but recommended).

## Installation

1. **Clone this repository:**

   ```bash
   git clone https://github.com/GurvirSingh04/Covid-Data-Visualiser.git
   cd Covid-Data-Visualiser
   ```

2. **Compile the application:**

   If you're using an IDE, open the project and build it. If you prefer the command line:

   ```bash
   javac *.java
   ```

3. **Run the application:**

   ```bash
   java ApplicationWindow
   ```

## File Structure

- `ApplicationWindow.java` - Main application window setup and initialisation.
- `BoroughMapController.java` - Controls the map visualisation of borough-specific data.
- `ChartController.java` - Manages the creation and interaction of charts.
- `CovidData.java` - Model class representing COVID-19 data entries.
- `CovidDataLoader.java` - Handles loading and parsing of COVID-19 data from external sources.
- `DateConverter.java` - Utility class for date conversions and formatting.
- `MainController.java` - Central controller managing the application's workflow.
- `StatisticsCalculator.java` - Performs statistical calculations on the data.
- `StatisticsCalculatorTest.java` - Unit tests for the `StatisticsCalculator` class.
- `StatisticsPanelController.java` - Manages the display of statistical data panels.
- `TableController.java` - Controls the tabular representation of data.

## How It Works

- The application loads COVID-19 data using the `CovidDataLoader` class.
- Data is processed and stored in `CovidData` objects.
- The `StatisticsCalculator` performs necessary statistical analyses.
- Visual representations are managed by controllers like `ChartController` and `BoroughMapController`.
- The `ApplicationWindow` initialises the GUI, integrating various components for user interaction.
