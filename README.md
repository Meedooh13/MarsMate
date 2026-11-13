# MarsMate

**Your mate on Mars — layers, route, and safety checks in one view, from NASA data.**

MarsMate is a layered, integrated view of a location or route on the Martian surface, built to help a human explorer plan and carry out a Marswalk while conducting new science along the way.

## The idea

NASA has explored Mars robotically for decades, mapping its surface and collecting many types of data — but that data isn't yet layered together in the combinations needed to plan a specific human mission.

MarsMate pulls together data from multiple NASA science missions into one view, so an astronaut can:

- Explore a site on a layered map built on NASA's Mars Trek
- Switch between basemaps and stack data layers — optical, topographic, thermal, spectral, and geologic
- Follow a rover-scouted traverse with waypoints, field notes, and hazards
- View the same map as a 3D planet, with landing sites and waypoints
- Check route length, EVA time, and walk-back safety for a Marswalk

The sites covered are Jezero Crater, explored by Perseverance, and Gale Crater / Mount Sharp, explored by Curiosity — including the boxwork formations Curiosity studied on lower Mount Sharp.

The site is static HTML/CSS/JS only, with no backend. Its map tiles stream live from NASA's Mars Trek WMTS service. No made-up data is used — everything comes from the NASA sources listed below, and waypoint positions along traverses are marked as approximate.

## How to use it

Open `index.html` in a browser (internet is required for the map tiles, Leaflet, and Three.js). Use the layer panel to switch basemaps and overlays, tap waypoints for details, and use the 2D Map / 3D Planet switch to view Mars as a globe.

## Data sources

- JPL Mars Trek — https://marstrek.jpl.nasa.gov
- USGS–NASA Planetary Geologic Mapping Program
- NASA Worldview — https://worldview.earthdata.nasa.gov
- Mars Perseverance Raw Images Gallery — https://mars.nasa.gov/mars2020/multimedia/raw-images/
- Curiosity route map for climbing lower Mount Sharp

## Team

Made by **The Tortured Devs Department**:

- Mohamed Elawany
- Kamel ismail
- Abdulrhuman Adel
- Ahmed Elmahdy

## Event

Built for the **NASA Space Apps Hackathon**, Local Event in Cairo, Elsewedy University of Technology - SUT.
