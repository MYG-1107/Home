# My Dream Home — Interactive 3D House Visualizer

A browser-based Three.js concept visualizer for a north-facing, three-level Indian family home. The north road, compound gate and north-east entrance approach are aligned in the current model.

## Floor-by-floor brief

### Ground floor — livestock and utility
- Enclosed storage / fodder room in the south-west.
- Open-sided covered cow and buffalo shed in the north-west.
- Fenced paddock with a real gate opening and grass / loafing area.
- Feeding manger, clean-water trough, calf pen and drainage channel.
- Wash / dairy utility point and screened manure / compost bay.
- Kitchen garden and planting beds towards the north-east / east.
- West-side staircase aligned with the stair core above.

### Second floor — 3BHK family home
- South-west master bedroom with an attached toilet.
- North-west second bedroom.
- South-side third bedroom.
- Hall / living room, dining area and L-shaped kitchen.
- Common toilet, pooja room, utility niche and north balcony.

### Third floor — 2BHK upper home
- South-west master bedroom and north-west second bedroom.
- Hall / living and dining areas.
- Kitchen, attached toilet and common toilet.
- Pooja room, family lounge / study and north balcony.
- Open terrace with indicative solar-panel and overhead-tank locations.

## Orientation and Vastu-inspired layout
- North = front / positive Z (+Z)
- East = right / positive X (+X)
- South = rear / negative Z (-Z)
- West = left / negative X (-X)

The model applies commonly followed Vastu preferences as indicative zoning: north / north-east entry, north-east pooja, south-east kitchen, south-west master bedroom, north-west secondary bedroom and a west-side stair core. Traditions vary; exact door pada and room placement should be reviewed against the measured plot and the family's chosen Vastu practice.

## Interactive navigation
- Select the whole house, ground floor, second floor or third floor.
- Drag to orbit, scroll to zoom and use touch gestures on mobile.
- Hold Shift while scrolling to move through floors; use Up / Down or Page Up / Page Down keys as alternatives.
- Choose a room chip to fly the camera to that room.
- Use Room tour to cycle through the selected floor's spaces.
- Switch to a top-down plan view, auto-rotate, zoom in / out or reset the camera.

## Technology
- HTML, CSS and JavaScript
- [Three.js](https://threejs.org/) and OrbitControls, loaded as browser ES modules from jsDelivr

## Animal-shelter design references
The cattle and buffalo areas are conceptual and include the functional elements identified in Indian husbandry guidance: ventilated shade, a loose/open paddock, manger, fresh-water access, non-slip / washable flooring and drainage. Useful reference material:
- [ICAR — Central Institute for Research on Buffaloes: Shelter Management](https://buffalopedianew.cirb.res.in/shelter-management/)
- [Dairy Knowledge — Handbook of Good-Dairy Husbandry Practices, Animal Housing](https://www.dairyknowledge.in/sites/default/files/book/fbook/handbook-dhp/files/assets/basic-html/page-107.html)
- [Tamil Nadu Agricultural University — Housing Management of Cattle and Buffalo](https://www.agritech.tnau.ac.in/expert_system/cattlebuffalo/Housing%20Management%20of%20Cattle%20and%20Buffalo.html)

## Run locally
Open `index.html` through a local static web server. ES module imports are not reliably supported when opening the file directly with `file://`.

## Important design note
This is an illustrative visualization, not a structural, approval or construction drawing. The three floors are separated vertically in the overview so their interiors can be inspected together; this exploded spacing is a presentation aid, not the actual building storey height. The model uses placeholder proportions because plot dimensions, true north bearing, road width, soil conditions, animal count and local building constraints have not been supplied. A qualified local architect / structural engineer must validate room dimensions, setbacks, foundations, columns, stair geometry, floor loads, drainage, ventilation, cattle accommodation, fire access and local approvals before construction. A veterinarian / dairy-husbandry professional should confirm animal-space and sanitation requirements for the intended herd.
