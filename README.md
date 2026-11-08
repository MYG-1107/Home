# My Dream Home — North-Facing Vastu-Inspired 3D House Concept

A browser-based Three.js concept visualizer for a three-level Indian family home. The model treats the front road and main entrance as **North**.

## North-facing orientation used in the model

- North = front / positive Z (+Z)
- East = right / positive X (+X)
- South = rear / negative Z (-Z)
- West = left / negative X (-X)

## House brief and Vastu-inspired zoning

- **Ground floor:** storage in the south-west, ventilated cattle shelter in the north-west, planting / garden area towards the north-east and east, a north-side entrance, and stairs along the west.
- **First floor — 3BHK:** master bedroom in the south-west, second bedroom in the north-west, third bedroom in the south, living towards the north, kitchen in the south-east, pooja niche in the north-east, west-side bathrooms, and north balcony.
- **Second floor — 2BHK:** bedrooms in the south-west and north-west, living towards the north / east, kitchen in the south-east, pooja niche in the north-east, west-side bathrooms, and north balcony / terrace.
- The central zone is kept comparatively open.

These placements reflect commonly followed Vastu preferences, not a universal rulebook. Exact recommendations, entrance placement (including door pada), and permissible room positions vary by Vastu school and by the actual site. Confirm the orientation with a site compass / survey and have the final layout reviewed by a qualified local architect and, if desired, a Vastu consultant.

## Interactive features

- Explore the full building or isolate any floor.
- Rotate, pan and zoom the 3D model.
- Switch to a top-down floor-plan view.
- Copy a plain-text design brief with orientation and Vastu zoning.
- Responsive layout for desktop, tablet and mobile.

## Technology

- HTML, CSS and JavaScript
- [Three.js](https://threejs.org/) and OrbitControls, loaded as browser ES modules from jsDelivr

## Run locally

Open `index.html` through a local static web server. ES module imports are not reliably supported when opening the file directly with `file://`.

## Important design note

This is an illustrative concept, not a structural, approval or construction drawing. The model uses placeholder proportions because the plot dimensions, true north bearing, road width and local building constraints have not been supplied. A qualified local architect / structural engineer must validate room sizes, setbacks, foundations, columns, stair geometry, drainage, cattle ventilation, fire access and local approvals before construction.
