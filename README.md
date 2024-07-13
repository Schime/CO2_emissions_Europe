# CO2 emissions visualization on Europe map
This project provides a visualization of CO2 emissions in European countries based on various factors. It includes interactive elements such as a map, bar charts, and dropdown menus to select and compare data for different countries.

# Project Structure
```
CO2EmissionsEurope/
│
├── index.html
├── style.css
├── europe_topology.json
├── world-data-2023.json
└── README.md
```

# Features
  - Interactive map of Europe with CO2 emissions data
  - Hover over countries to see CO2 emissions information
  - Click on a country to view detailed data in a bar chart
  - Compare data between two selected countries

# Getting Started
## Prerequisites
To run this project, you need to have Python installed on your machine. You can download and install Python from [here](https://www.python.org/downloads/).

## Instructions
  - To view a website, open [this](https://schime.github.io/CO2_emissions_Europe/)
  - To open a website localy, from Visual Studio Code run the following commands
    - Locate a project folder using
      ```
      cd "project_folder_path_location"
      ```
    - Open the terminal in VS Code and run
      ```
      python -m http.server
      ```

# Project Structure
  - index.html: Contains the HTML structure and D3.js scripts to render the map and charts
  - style.css: Defines the styles for the HTML elements and ensures proper layout and design
  - europe_topology.json: Topological data for European countries, necessary for rendering the map
  - world-data-2023.json: Provides the dataset used for displaying various statistics in the visualization

# Functionalities
  - Map
    - Displays a map of Europe with countries color-coded based on CO2 emissions
    - Hover over a country to see its name and CO2 emissions
    - Click on a country to display detailed data and compare it with another country
    - 
