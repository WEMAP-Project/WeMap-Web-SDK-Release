# WeMap SDK

-------------
## Version 1.4
## Date: 2020/08/17

### ✨ Feautures

1. Directions: 
    - Update UI directions support multiple route
2. Search:
	- Support search by user location
3. Fix bugs and improvements performance

-------------
## Version 1.3
## Date: 2020/06/20

### ✨ Feautures

1. Directions: 
    - Support another engine for directions
    - Update UI directions
    - Support display order of engine/vehicles
2. Fix bugs and improvements performance

### ⚠ Breaking changes
- Support another engine for directions 

-------------

## Date: 2020/03/31

### ✨ Feautures

1. Interface:
    1. Supported mobile Browser
    2. Fix bugs and improvements performance

### ⚠ Breaking changes
- Supported mobile Browser

-------------
## Version 1.2

## Date: 2020/03/27

### ✨ Feautures

1. Place detail:
    1. Change format Latitude and Longitude

2. WeFilter:
    1. Added Wefilter: Filter by categories of PoI on the map

### ⚠ Breaking changes
- Added WeFilter

-------------
## Version 1.1

## Date: 2020/03/17

### ✨ Feautures
1. WeGeolocationControl: Fix bugs and improvements performance.

-------------
## Version 1.1

## Date: 2020/03/16

### ✨ Feautures
1. Reverse:
    1. update url of polygon reverse
    2. maximum allowed distance for reverse is saved in config.js
	3. Fix format address
2. WeGeolocationControl: A control provides a button that uses the browser's geolocation API to locate the user on the map.
3. WeGeocode
	1. Add fly to when howver to search list or press enter in search input
	2. Added zoom to polygon and show polygon

-------------
## Version 1.0

### Date: 2020/03/05

### 🍏 Improvements

- Fix bugs and improvements performance
- Update directions icon
- Changed address format in place detail 

-------------
## Version 0.3

### Date: 2020/03/02

### ✨ Features

1. Place detail:
    1. Remove unnecessary info

-------------
## Version 0.2

### Date: 2020/03/02

### ✨ Features

1. Map: Init map and change option
    1. key: for using map api and replace `accessToken` -> `key`
    2. style: changed option `default` | `bright` | `dark`
    3. reverse: point/polygon
    4. url control: utility for get url, update url, delete url. Currently always set `urlController: "true"`
    5. hover: Changed `cursor: "point"` when hover to icon on map
    6. Click show detail: Show point detail in left sidebar when clicked a point or click to reverse banner
    7. Switch to route: When click to icon direction reverse banner
    8. Right click: Added context menu when right click to map: `What's here?`, `Direction from here`, `Directions to here`

2. Search
    1. Engine: Added Pelias Geocode Engine
    2. Suggestion: Suggestion 10 result search when input char > `suggestion.min_chars` default is `4`
    3. Switch suggestion list using keyboard page up and page down
    3. Enter search: Show list result more exactly
    4. Show place detail when click search search suggestion list or enter search list
    5. Click to icon direction switch to `Directions` with input current place to destination
    6. Show hide marker base on suggestion list and search list

3. Route
    1. Click to map add Origin and Destination to input direction
    2. Engine: Geocode Pelias
    3. Switch between Origin and Destination
    4. Set default vehicle is `driving`
    5. When in directions click to map, if Origin and Destination
already have information then show reverse
    6. Add control button to Search input

### ★ Future
1. Place:
    1. Rating:
    2. Comment:

### 🍏 Improvements

### 🐞 Bug Fixes

### 🐛 Bug Created

### ⚠ Breaking changes
- Added URL control
- Added reverse polygon

-------------
## Version 0.1

- Init WeMap SDK
