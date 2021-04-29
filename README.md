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
    * Go to ArcGIS online rest url for the webmap: https://accsmaps.maps.arcgis.com/sharing/rest/content/items/**"webmap-id"**/data?f=pjson
    * Paste json for web map after "var webmapJSON = "

## Usage
The ACCS Calcite Map Template is a modified version of the ESRI Calcite Maps Framework, which is available under the Apache 2.0 License. We have modified the template to fit the theme, branding, and needs of the Alaska Center for Conservation Science. We have licensed the modified version under the Apache 2.0 License as well. However, we encourage potential users to use the maintained [ESRI Calcite Maps Framework](https://github.com/Esri/calcite-maps).

### ACCS Calcite Maps Template
* Map template should be maintained to match current version of ESRI Calcite Maps Frameworj and incorporate new features as added.

## Credits
[ESRI Calcite Maps Framework](https://github.com/Esri/calcite-maps)

### Built With
* Notepad ++
* ESIR 
* ArcGIS Online

### Authors

* **Timm Nawrocki** - *Alaska Center for Conservation Science, University of Alaska Anchorage*

### Usage Requirements
Specified in the [ESRI Calcite Maps Framework](https://github.com/Esri/calcite-maps).

### License
Modified from: [ESRI Calcite Maps Framework](https://github.com/Esri/calcite-maps) Copyright 2015 Esri

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

A copy of the license is available in the repository's license.txt file.
