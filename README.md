# ACCS Calcite Map Template

A javascript, css, and html template based on the Calcite Maps framework for simple data viewer applications.

## Getting Started

These instructions will enable you to deploy the ACCS Calcite Map on a server.

### Prerequisites
The "lib" and "dist" folders from the [Calcite Maps Framework](https://github.com/Esri/calcite-maps) must be included in the same directory as the map.html and custom.css.

### Installing
1. Download the [Calcite Maps Framework](https://github.com/Esri/calcite-maps) repository and add the "lib" and "dist" folders to the server partition. Add the map.html and custom.css to the same server partition.
2. If necessary, update the relative path links in the map.html to reflect the locations of the Calcite Maps Framework and the custom.css.
3. Update all placeholder text fields in map.html to reflect the content.
4. Add a web map using the following steps:
    * Make a map using ArcGIS online and share publicly
    * Go to ArcGIS online rest url for the webmap: https://accsmaps.maps.arcgis.com/sharing/rest/content/items/**"webmap id"**/data?f=pjson
    * Paste json for web map after "var webmapJSON = "

## Usage

### ACCS Calcite Maps Template
* Map template should be maintained to match current version of Calcite Maps and incorporate new features as added.

## Credits

### Built With
* Notepad ++
* Calcite Maps Framework
* ArcGIS Online

### Authors

* **Timm Nawrocki** - *Alaska Center for Conservation Science, University of Alaska Anchorage*

### Usage Requirements

None

### License

This project is private and can be used by Alaska Center for Conservation Science and collaborators.
