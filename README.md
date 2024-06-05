# leaflet-challenge
# Earthquake Visualization with Leaflet

Welcome to the leaflet-challenge repository! This project was completed as part of Module 15 Challenge, where the task was to create a meaningful way to visualize earthquake data provided by the United States Geological Survey (USGS). The main goal is to better educate the public and other government organizations about natural hazards and the impacts of climate and land-use change.


## Background
The United States Geological Survey (USGS) is responsible for providing scientific data about natural hazards, ecosystem health, and environmental changes. They collect vast amounts of data worldwide but need effective visualization tools. This project aims to develop a tool to visualize USGS earthquake data to help secure more funding and educate the public.

# Instructions
## Part 1: Create the Earthquake Visualization

Get your dataset:
Visit the USGS GeoJSON Feed page and choose a dataset (e.g., "All Earthquakes from the Past 7 Days").
Use the URL of the chosen dataset to pull in the data for visualization.

## Visualize the data using Leaflet:
- Create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
- The data markers should reflect the magnitude of the earthquake by size and the depth by color. Larger markers indicate higher magnitudes, and darker colors indicate greater depths.
- Include popups with additional information about the earthquake when a marker is clicked.
- Create a legend to provide context for the map data.


## Files
The project includes the following key files:
- index.html: The main HTML file that loads the map.
- style.css: The CSS file for styling the map and legend.
- logic.js: The JavaScript file containing the logic for fetching data, creating the map, and plotting the earthquakes.

## Installation
To run this project locally, follow these steps:
Clone the repository to your local machine:
- bash
- Copy code
- git clone https://github.com/yourusername/leaflet-challenge.git

Navigate to the project directory:
- bash
- Copy code
- cd leaflet-challenge
- Open index.html in your preferred web browser.

## Usage
Once the project is set up and running, you will see an interactive map displaying earthquake data. The markers vary in size based on the earthquake's magnitude and in color based on the depth. Clicking on a marker will show a popup with additional details about the earthquake. The legend on the map helps interpret the marker sizes and colors.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:
- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes.
- Commit your changes (git commit -m 'Add new feature').
- Push to the branch (git push origin feature-branch).
- Open a Pull Request.
