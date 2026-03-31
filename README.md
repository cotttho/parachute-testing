# Homebuilt Parachute Wind Tunnel Build and Test Guide

## Purpose

This guide walks you through:

- buying the materials for a practical homebuilt wind tunnel
- building a vertical test rig for small parachute models
- building several parachute shapes and sizes
- running repeatable comparative tests

The design below is meant for **small model parachutes**, not full-size human-rated canopies. It is optimized for comparing shapes, vent sizes, line lengths, and materials under controlled airflow.

## Recommended Tunnel Configuration

Build a **vertical, open-return, low-speed tunnel** with this airflow path:

1. box fan
2. plenum
3. screen layers
4. honeycomb flow straightener
5. contraction section
6. clear test section
7. diffuser / exhaust

This setup is better for parachute work than a simple horizontal fan-on-a-table arrangement because it lets the canopy inflate and hover in a more realistic orientation.

## Target Size

Use these baseline dimensions:

- Fan: `20 in x 20 in` box fan
- Plenum: `20 in x 20 in x 20 in`
- Honeycomb depth: `4 in to 6 in`
- Contraction: `20 in x 20 in` down to `16 in x 16 in` over `18 in`
- Test section: `16 in x 16 in x 24 in`
- Diffuser: `16 in x 16 in` out to about `20 in x 20 in` over `18 in to 24 in`

Keep model parachutes small enough that the inflated canopy does not occupy too much of the test section. A good starting range is:

- canopy diameter: `4 in to 6 in`
- absolute upper end: around `7 in to 8 in`, depending on shape

## Schematics

These are text schematics for layout and cutting. They are not meant to replace shop drawings, but they are accurate enough to build the tunnel and keep the module sizes consistent.

### Overall Side View

```text
                    OPEN TOP / EXHAUST
                 ┌──────────────────────┐
                 │       DIFFUSER       │
                 │   16x16 to 20x20     │   18-24 in tall
                 │      expanding       │
                 └──────────┬───────────┘
                            │
                 ┌──────────┴───────────┐
                 │     TEST SECTION     │
                 │       16x16          │   24 in tall
                 │    clear windows     │
                 │    parachute here    │
                 └──────────┬───────────┘
                            │
                 ┌──────────┴───────────┐
                 │     CONTRACTION      │
                 │   20x20 to 16x16     │   18 in tall
                 │    gently tapered    │
                 └──────────┬───────────┘
                            │
                 ┌──────────┴───────────┐
                 │  HONEYCOMB + SCREEN  │   4-6 in honeycomb
                 │  2-3 screen layers   │
                 └──────────┬───────────┘
                            │
                 ┌──────────┴───────────┐
                 │       PLENUM         │
                 │        20x20         │   20 in tall
                 │   sealed settling    │
                 └──────────┬───────────┘
                            │
                 ┌──────────┴───────────┐
                 │       BOX FAN        │
                 │        20 in         │
                 │     blowing up       │
                 └──────────────────────┘
```

### Front View of Test Section

```text
                 16 in inside width
            ┌──────────────────────────┐
            │            o             │  <- top-center eye screw
            │            |             │
            │           / \            │
            │         ./   \.          │
            │        /       \         │
            │        \       /         │  <- inflated canopy
            │         \.___./          │
            │            |             │
            │            |             │
            │           [ ]            │  <- payload washers / sinkers
            │                          │
            └──────────────────────────┘
                    24 in inside height
```

### Top View of Tunnel Sections

```text
PLENUM / SCREEN / HONEYCOMB PLAN VIEW

       outside frame approx 20x20 in
     ┌──────────────────────────────┐
     │[][][][][][][][][][][][][][][]│
     │[][][][][][][][][][][][][][][]│  <- honeycomb cells
     │[][][][][][][][][][][][][][][]│
     └──────────────────────────────┘

TEST SECTION PLAN VIEW

       inside clear area 16x16 in
     ┌──────────────────────────────┐
     │                              │
     │           parachute          │
     │           centerline         │
     │                              │
     └──────────────────────────────┘
```

### Contraction Panels

Build the contraction from four tapered panels.

```text
SIDE PANEL OF CONTRACTION

      18 in length
   <------------------>

   20 in end       16 in end
   ┌──────────┐    ┌────────┐
   │          └────┘        │
   │                        │
   └────────────────────────┘

The taper is gentle. Mirror this geometry on opposite sides.
```

### Diffuser Panels

The diffuser is the reverse of the contraction.

```text
SIDE PANEL OF DIFFUSER

      18-24 in length
   <--------------------->

   16 in end       20 in end
   ┌────────┐      ┌──────────┐
   │        └──────┘          │
   │                          │
   └──────────────────────────┘
```

## Shopping List

Use the "Search / Example" column as the search phrase on the retailer site if local stock differs.

### A. Tunnel Structure

| Item | Qty | Where to buy | Search / Example | Notes |
|---|---:|---|---|---|
| 20 in box fan | 1 | Home Depot, Walmart, Target, Amazon | `20 in box fan` | Main airflow source. A model with 3 speeds is enough. |
| 1 in x 2 in x 8 ft furring strips | 10 to 14 | Home Depot | `1x2 furring strip 8 ft` | Frame for plenum, contraction, test section, diffuser. |
| 1/4 in plywood, hardboard, or foam board panels | 4 to 6 sheets | Home Depot | `project panel`, `hardboard panel`, `foam board insulation` | Use for opaque walls and duct sections. |
| Clear acrylic or polycarbonate sheet | 2 panels | Home Depot, Lowe's, Amazon | `clear acrylic sheet 24 in x 36 in` | For test section windows. Polycarbonate is tougher; acrylic is cheaper. |
| Wood screws, #6 or #8, 1-1/4 in | 1 box | Home Depot | `wood screws 1-1/4 in` | Frame assembly. |
| Small pan-head screws + washers | 1 box each | Home Depot | `pan head sheet metal screws`, `finish washers` | Better for mounting plastic panels without cracking them. |
| Construction adhesive | 1 tube | Home Depot | `construction adhesive` | Optional for stiffening panel joints. |
| Clear silicone caulk | 1 tube | Home Depot | `clear silicone caulk` | Seal air leaks. |
| Foam weatherstrip tape | 1 roll | Home Depot | `foam weatherstrip tape` | Seal fan mount and removable panels. |
| Duct tape or HVAC foil tape | 1 roll | Home Depot | `duct tape` or `foil tape` | Temporary seals and edge cleanup. |

### B. Flow Conditioning

| Item | Qty | Where to buy | Search / Example | Notes |
|---|---:|---|---|---|
| Fiberglass window screen | 1 roll | Home Depot | `fiberglass window screen roll` | Use 2 to 3 layers ahead of the honeycomb. |
| Hardware cloth, 1/4 in mesh | 1 roll or sheet | Home Depot | `1/4 in hardware cloth` | Support grid and safety guard. |
| Honeycomb material | enough for 20 in x 20 in x 4 in to 6 in | Home / Amazon / hardware store | `paper mailing tubes`, `drinking straws`, `short pvc couplers`, `egg crate light diffuser` | Use any straight, short cells to reduce swirl. |
| Zip ties or hot glue sticks | 1 pack | Home Depot / Amazon | `zip ties` or `hot glue sticks` | To assemble the honeycomb block. |

### C. Test Rig and Instrumentation

| Item | Qty | Where to buy | Search / Example | Notes |
|---|---:|---|---|---|
| Fishing line | 1 spool | Amazon, Walmart, sporting goods store | `monofilament fishing line 10 lb` | For suspension lines and test fixtures. |
| Ball-bearing swivels or snap swivels | 1 pack | Amazon, Walmart, sporting goods store | `fishing swivels` | Reduces twist during tests. |
| Small hooks, cup hooks, or eye screws | 6 to 10 | Home Depot | `small eye screw` | Anchor points in the test section. |
| Digital luggage scale or hanging scale | 1 | Amazon, Walmart | `digital luggage scale` | Useful for drag-force and line-tension measurements. |
| Handheld anemometer | 1 | Amazon, Walmart | `handheld anemometer` | Measure airspeed in the test section. |
| Tape measure | 1 | Home / Home Depot | `tape measure` | For layout and test repeatability. |
| Spring clamps or binder clips | 6 to 10 | Home Depot / office supply store | `spring clamps` or `binder clips` | Quick mounting and repeatable rigging. |
| Washers, nuts, or fishing sinkers | assorted | Home Depot / sporting goods store | `fender washers` or `split shot sinkers` | Payload weights. |

### D. Parachute-Making Materials

| Item | Qty | Where to buy | Search / Example | Notes |
|---|---:|---|---|---|
| Lightweight plastic sheet | 1 roll or a few bags | Home / grocery / Amazon | `trash bags`, `dry cleaning plastic`, `poly drop cloth` | Good for early prototypes. |
| Ripstop nylon or polyester | 1 to 2 yd | Amazon, fabric store, Ripstop by the Roll | `ripstop nylon fabric` | Better for consistent test articles. |
| Braided thread or light cord | 1 spool | Amazon / craft store | `braided line`, `upholstery thread` | Suspension lines. |
| Fabric tape or clear packing tape | 1 roll | Home Depot / Amazon | `clear packing tape` | Reinforce attachment points. |
| Hole punch or leather punch | 1 | Home Depot / Amazon | `single hole punch` | Clean line holes in plastic canopies. |
| Scissors or rotary cutter | 1 | Home / craft store | `fabric scissors` | Clean canopy cuts. |
| Compass, ruler, protractor, marker | 1 each | Home / office store | `drawing compass`, `protractor` | Pattern layout. |

### E. Optional Upgrades

| Item | Qty | Where to buy | Search / Example | Notes |
|---|---:|---|---|---|
| Variable fan speed controller rated for the fan type | 1 | Amazon / electrical supplier | `fan speed controller` | Only use if it is compatible with the fan motor. Many box fans already have 3 speeds. |
| Second identical box fan | 1 | Same as first fan | `20 in box fan` | Can increase pressure if stacked carefully with a spacing section. |
| LED shop light | 1 | Home Depot | `LED shop light` | Better slow-motion video and shape observation. |
| Smartphone tripod | 1 | Amazon / Walmart | `phone tripod` | Fixed camera angle for comparison tests. |

## Tools You Will Need

- drill / driver
- drill bits
- jigsaw or circular saw
- utility knife
- straightedge
- square
- hot glue gun if you use straw or tube honeycomb
- clamps
- safety glasses
- gloves for hardware cloth handling

## Build Overview

The build is easiest if you treat it as five separate modules:

1. fan mount
2. plenum
3. flow straightener
4. contraction
5. clear test section plus diffuser

Build each module square and seal leaks as you go.

## Suggested Cut Plan

This is a practical cut plan, not a precision cabinetmaking plan. Adjust to the exact outer size of your fan and your chosen wall material thickness.

### 1x2 Frame Pieces

Cut enough material for:

- 4 verticals at `24 in` for the test section
- 8 horizontals at `16 in` for the test section top and bottom frames
- 4 verticals at `20 in` for the plenum
- 8 horizontals at `20 in` for the plenum top and bottom frames
- 4 contraction corner members at about `18 in`
- 4 diffuser corner members at about `18 in to 24 in`
- extra blocking and braces as needed

### Panel Pieces

Cut panels for:

- plenum sides
- contraction walls
- diffuser walls
- at least 2 clear window panels for the test section
- 1 removable access panel if possible

### Example Panel Dimensions

Use these as starting dimensions if you are building with thin sheet material over a `1x2` frame.

```text
PLENUM PANELS
- 4 side panels:       20 in x 20 in

TEST SECTION PANELS
- 2 clear side panels: 24 in x 16 in
- 1 rear panel:        24 in x 16 in
- 1 front access side: 24 in x 16 in

CONTRACTION PANELS
- 2 opposing panels:   18 in long, tapering 20 in to 16 in
- 2 opposing panels:   18 in long, tapering 20 in to 16 in

DIFFUSER PANELS
- 2 opposing panels:   18-24 in long, tapering 16 in to 20 in
- 2 opposing panels:   18-24 in long, tapering 16 in to 20 in
```

### Frame Layout Concept

```text
TEST SECTION FRAME

Top frame:     16 x 16 in square
Bottom frame:  16 x 16 in square
Verticals:     4 pieces at 24 in

PLENUM FRAME

Top frame:     20 x 20 in square
Bottom frame:  20 x 20 in square
Verticals:     4 pieces at 20 in
```

## Detailed Build Instructions

### Step 1: Mount the Fan

1. Measure the fan body, not just the blade diameter.
2. Build a square base frame from `1x2`s that supports the fan snugly.
3. Orient the fan to blow **upward**.
4. Add weatherstrip where the fan contacts the frame to reduce air leakage and vibration.
5. Add a hardware-cloth safety guard anywhere fingers could reach the blades.

Tip:
If the fan rattles, fix that now. Vibration makes the entire tunnel noisier and less repeatable.

### Step 2: Build the Plenum

1. Build a `20 in x 20 in x 20 in` box above the fan.
2. Seal the inside edges with silicone caulk.
3. Make one side removable if you want easier access to the screen and honeycomb assembly.
4. Keep the inside as smooth as practical.

The plenum lets the air settle before it enters the straightener.

### Step 3: Add the Screen Layers

1. Stretch one layer of fiberglass window screen across the full cross-section near the top of the plenum.
2. Add a second layer `1 in to 2 in` above the first.
3. Add a third layer if the flow still looks uneven during testing.
4. Mount the screen flat and taut.

Do not let the screen sag into the airflow. Uneven screen tension creates uneven flow.

### Step 4: Build the Honeycomb Flow Straightener

1. Make a grid of straight cells `1/2 in to 1 in` wide and `4 in to 6 in` long.
2. Good materials:
   - bundles of drinking straws
   - short cardboard tubes
   - short pieces of thin-wall PVC
   - egg-crate style light diffuser backed by another layer
3. Pack the cells tightly into a `20 in x 20 in` frame.
4. Glue or tie the cells so they cannot shift.
5. Mount the honeycomb above the screen layers.

The goal is to remove swirl from the fan, not to create a perfect laboratory settling chamber.

### Step 5: Build the Contraction Section

1. Build a transition from `20 in x 20 in` down to `16 in x 16 in` over about `18 in`.
2. Use four gently sloped panels.
3. Avoid abrupt steps or sharp interior corners.
4. Seal joints on the inside.

This section improves flow uniformity and increases airspeed entering the test section.

### Step 6: Build the Test Section

1. Build a rigid `16 in x 16 in x 24 in` frame.
2. Install clear panels on at least 2 sides.
3. Add an access panel or removable top for rigging tests.
4. Install small eye screws at the top center and optionally at the side corners.
5. Add a removable measurement scale on one clear wall:
   - tape a printed inch grid or ruler strip to the outside
   - this helps you estimate inflation diameter and oscillation amplitude

The test section should be the straightest and cleanest part of the tunnel.

### Step 7: Add the Diffuser

1. Build an expanding section above the test section, going from `16 in x 16 in` back toward `20 in x 20 in`.
2. Use a length of `18 in to 24 in`.
3. Leave the top open.

This reduces the chance of a harsh exit flow disturbing the test section.

### Step 8: Seal and Check Alignment

1. Inspect every seam for leaks.
2. Seal obvious gaps with caulk or tape.
3. Confirm that the test section is centered over the fan.
4. Confirm that the honeycomb is not tilted or partially blocked.

## First Flow Check

Before testing parachutes:

1. Turn the fan on low.
2. Hold short pieces of thread or yarn at several points in the test section.
3. Look for:
   - strong sideways motion
   - dead spots
   - obvious swirl
4. If the flow is poor:
   - add another screen layer
   - improve the honeycomb
   - seal leaks
   - reduce obstructions in the test section

You do not need perfect flow. You do need repeatable flow.

## Building the Parachute Test Articles

Make several canopies that differ by only one variable at a time.

### Recommended Starter Set

Build these four shapes first:

1. flat circular canopy
2. flat circular canopy with spill hole
3. conical canopy
4. cruciform canopy

For each shape, build at least 3 sizes:

- `4 in`
- `5 in`
- `6 in`

Keep the suspension line material and payload attachment method the same across all tests.

## Parachute Pattern Instructions

### Pattern Schematic Reference

These simple plan-view sketches are enough to lay out the first set of canopies.

```text
1. FLAT ROUND

          _________
      .-''         ''-.
    .'                 '.
   /                     \
  |           +           |   + = center mark
   \                     /
    '.                 .'
      '-.___________.-'

2. FLAT ROUND WITH SPILL HOLE

          _________
      .-''   ___   ''-.
    .'      /   \      '.
   /       |  +  |       \
  |         \___/         |
   \                       /
    '.                   .'
      '-._____________.-'

3. CONICAL CANOPY PATTERN

          _________
      .-''         ''-.
    .'               __'.
   /              _.-'   \
  |          _..-'        |   Cut out a wedge,
   \     _.-'            /    then join cut edges
    '._-'              .'     to form the cone.
       '-._________.-'

4. CRUCIFORM

             ┌───────┐
             │       │
     ┌───────┼───────┼───────┐
     │       │   +   │       │
     └───────┼───────┼───────┘
             │       │
             └───────┘
```

### A. Flat Circular Canopy

1. Draw a circle on plastic or ripstop using a compass or a string pivot.
2. Cut the circle cleanly.
3. Mark 6, 8, or 12 equally spaced attachment points around the edge.
4. Reinforce each point with a small square of tape.
5. Punch a small hole through each reinforced point.
6. Cut equal line lengths.
7. Tie or tape the lines to the canopy.
8. Gather all lines to a common payload loop.

Good starting line length:

- `1.0 x` to `1.5 x` canopy diameter

Example:

- 5 in canopy -> try 5 in, 6.5 in, and 7.5 in line lengths

### B. Flat Circular Canopy With Spill Hole

1. Start with the circular canopy above.
2. Cut a centered vent hole.
3. Test several vent diameters:
   - `5%`
   - `10%`
   - `15%`
   - `20%` of canopy diameter

This usually improves stability at some drag cost.

### C. Conical Canopy

1. Cut a circular sector instead of a full circle.
2. Bring the cut edges together to form a cone.
3. Tape or sew the seam.
4. Add evenly spaced suspension lines around the skirt.

Start with a shallow cone first. Very steep cones can be stable but may not be directly comparable to flat round canopies.

### D. Cruciform Canopy

1. Draw a cross made from 5 equal squares.
2. Round or leave the arm ends square.
3. Attach lines near the four outer arm ends and intermediate points if needed.
4. Keep geometry symmetric.

Cruciform parachutes often show better stability than simple flat circles.

## Payload Rig

Create a standard payload rig so every test article uses the same attachment and weight setup.

Recommended rig:

- top swivel
- canopy suspension lines
- lower swivel or loop
- removable weight stack made from washers or sinkers

Make several payload masses, for example:

- light
- medium
- heavy

You do not need exact target values at first. What matters is that the same weights are used repeatedly across designs.

## Test Setup

### Instrument Placement

1. Mount the anemometer in the test section centerline when mapping airflow.
2. During parachute tests, move it out of the way and use a previously calibrated fan setting if needed.
3. Put a ruler or grid behind the canopy in camera view.
4. Mount your phone or camera on a tripod at a fixed angle.

### Rigging the Test Article

1. Attach the canopy to the top-center eye screw with a swivel.
2. Position the canopy so it can rise into clean airflow without touching the walls.
3. Confirm the lines are untwisted.
4. Start with the lightest payload.

## Test Program

Run the same sequence for every parachute.

### Test 1: Inflation Threshold

Purpose:
Find the lowest airflow that inflates the canopy fully.

Procedure:

1. Set the fan to its lowest setting.
2. Place the canopy in the airstream.
3. Record whether it:
   - fails to open
   - partially opens
   - fully inflates
4. Increase airflow or switch to the next fan speed.
5. Record the first condition where full inflation is repeatable.

Record:

- fan setting
- measured airspeed if available
- time to full inflation
- any asymmetry during opening

### Test 2: Hover Stability

Purpose:
Compare how steady the parachute remains once inflated.

Procedure:

1. Adjust airflow until the payload hovers steadily in the middle of the test section.
2. Observe for at least `20 to 30 seconds`.
3. Record:
   - side-to-side swing
   - rotation
   - breathing or pulsing
   - partial collapse
   - line twist

Simple scoring system:

- `1` = very unstable
- `2` = unstable
- `3` = usable
- `4` = stable
- `5` = very stable

### Test 3: Drag Comparison

Purpose:
Compare which canopy generates more drag.

Procedure A: Constant Payload

1. Use the same payload mass for all test articles.
2. Increase airflow until the canopy hovers at a marked height.
3. Record the airspeed.

Interpretation:

- lower required airspeed = more effective drag for that payload

Procedure B: Constant Airspeed

1. Set the airflow to a fixed airspeed.
2. Increase payload mass until the parachute can no longer maintain stable hover.
3. Record the maximum stable payload.

Interpretation:

- higher supported payload = more effective drag at that test condition

### Test 4: Disturbance Recovery

Purpose:
See how well the canopy recovers after a perturbation.

Procedure:

1. Bring the parachute to stable hover.
2. Gently displace the payload sideways by hand before releasing, or briefly interrupt the flow with a card outside the tunnel.
3. Record:
   - whether it recenters
   - how many oscillations occur
   - whether it collapses
   - whether it spins up

### Test 5: Repeatability

Purpose:
Check whether the result is real or just noise.

Procedure:

1. Repeat each test at least 3 times.
2. Average your results.
3. If one run is very different, inspect:
   - line symmetry
   - attachment damage
   - material wrinkles
   - changes in airflow

## Variables to Change One at a Time

When comparing designs, only change one variable at a time:

- canopy diameter
- canopy shape
- spill-hole diameter
- number of suspension lines
- line length
- material type
- material porosity
- payload mass

If you change multiple variables together, it becomes much harder to interpret the results.

## Suggested Test Matrix

Start with a small, disciplined matrix:

| Test ID | Shape | Diameter | Spill Hole | Line Length | Material | Payload | Fan Setting / Airspeed |
|---|---|---|---|---|---|---|---|
| 1 | Flat round | 4 in | none | 1.0D | plastic | light | record |
| 2 | Flat round | 4 in | 10% | 1.0D | plastic | light | record |
| 3 | Flat round | 5 in | none | 1.0D | plastic | light | record |
| 4 | Flat round | 5 in | 10% | 1.0D | plastic | light | record |
| 5 | Cone | 5 in equivalent | none | 1.0D | plastic | light | record |
| 6 | Cruciform | 5 in span | n/a | 1.0D | plastic | light | record |

After that, repeat the best two or three designs in ripstop fabric.

## Optional Drag Calculation

If you want a rough comparative drag-area estimate during stable hover, use:

`CdA = 2mg / (rho * V^2)`

Where:

- `CdA` = effective drag area
- `m` = payload mass in kilograms
- `g` = `9.81 m/s^2`
- `rho` = air density, use about `1.2 kg/m^3` for a rough estimate
- `V` = airspeed in `m/s`

This is only approximate in a home tunnel, but it is useful for comparing designs.

## Data Sheet Template

Copy this for each run:

```text
Date:
Tunnel configuration:
Fan setting:
Measured centerline airspeed:

Parachute ID:
Shape:
Diameter / span:
Material:
Spill-hole size:
Number of lines:
Line length:
Payload mass:

Inflation result:
Time to inflate:
Hover height:
Oscillation amplitude:
Rotation:
Collapse events:
Recovery after disturbance:
Notes:
```

## Safety Notes

- keep hands clear of fan blades
- guard all fan openings with mesh
- wear gloves when handling hardware cloth
- do not leave the fan running unattended
- keep loose strings and fabric away from the fan intake before the plenum is closed
- if you use a speed controller, verify it is compatible with the fan motor type

## Practical Tuning Tips

- If the parachute spins constantly, check line symmetry first.
- If the canopy collapses repeatedly, try a spill hole or longer lines.
- If the airflow is visibly swirling, improve the honeycomb before changing parachute geometry.
- If the canopy sticks to one side, re-center the rig and inspect for wall interference.
- If the tunnel is too weak, reduce canopy size before trying to scale up the fan system.

## Recommended Build Order

If you want the fastest path to a working setup, do this in order:

1. build fan mount and plenum
2. add screens and a simple honeycomb
3. build the clear test section
4. test airflow with yarn
5. add the contraction
6. seal leaks
7. build three simple round parachutes
8. start testing before adding upgrades

This gets you useful results sooner than trying to perfect every tunnel detail up front.
