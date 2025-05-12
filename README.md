# Graphica-Interactive-Dashboard-for-TB-

## Overview

This project presents an interactive, multi-visualization data dashboard built using HTML, CSS, JavaScript, and D3.js. It offers dynamic, exploratory data visualizations through a clean and responsive user interface.

## Team Members

* Muhammad Abubakar Nadeem (22I-2003)
* Sahil Kumar (22I-2048)
* Meher Amir (22I-1973)

## Features

* Responsive sidebar navigation with menu toggle
* Integration of multiple D3.js-based interactive visualizations
* Hover effects, tooltips, node selection, and record details
* Embedding and full-page view capabilities for each visualization

## Dashboard Visualizations

1. *Graph 1: Force-Directed Graph* (index.html)

   * Displays relationships between countries and TB causes.
   * Clickable nodes to show associated data.
   * Dynamic tooltips and link labels.

2. *Graph 2: Choropleth Map* (index2.html)

   * Geographic data representation (requires data and implementation).

3. *Graph 3: TB Data Visualization* (index3.html)

   * Specific TB-related metrics across countries (implementation assumed).

4. *Graph 4: Hierarchical Tree Map* (index4.html)

   * Visual hierarchy representation using rectangle areas.

5. *Graph 5: Sunburst Chart* (index5.html)

   * Circular hierarchical visualization (nested data structure).

## Technologies Used

* HTML5, CSS3, JavaScript
* D3.js (v7)
* Responsive Grid Layout and Fixed Side Menu
* Interactive UI controls with hover and click events

## Usage Instructions

1. Clone or download the repository.
2. Ensure all HTML files (index.html to index5.html) are in the same directory.
3. Launch dashboard.html in a browser.
4. Click on any menu item to view the corresponding graph.
5. In index.html, interact with nodes to explore TB relationships and data.

## Data File

* updated_tb_dataset.csv: Required for index.html (Force-Directed Graph)
* Contains fields: country, TB Cause, Relationship Type, People Affected, Deaths, path, latitude, longitude

## File Structure

* dashboard.html – Main dashboard page with sidebar menu
* index.html – Force-Directed Graph with interactivity
* index2.html to index5.html – Placeholder or implemented additional visualizations
* updated_tb_dataset.csv – Data source file for graph rendering

## Highlights

* Uses force simulation for dynamic positioning of nodes
* Allows node selection and displays related records
* Edge labels for enhanced relationship context
* Seamless navigation between visualizations

## Acknowledgements

This dashboard was developed as a course project and demonstrates frontend visualization and data interaction skills using D3.js.
