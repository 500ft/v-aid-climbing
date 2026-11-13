# V-Aid: tactile climbing interface

Four prototype generations demonstrated a gantry-addressed 12 × 12 tactile array with compliant locking pins. Fourteen route patterns are reported; event-level reliability counts were not retained.

![V-Aid: tactile climbing interface built hardware](images/final-integrated-prototype.jpg)

## My contribution

Pin CAD, guide-feature and clamp-interface iteration, FDM prototype fabrication, laser-cut housing integration, and functional route testing.

My mechanical work covered the pin profile, guides and locking interface, printed prototypes, laser-cut housing and integration. Image/colour selection, grid conversion and fixed-coordinate control code were team work.

## How the mechanism works

Team code selects an image colour, simplifies the selection to a 12 × 12 grid and addresses fixed pin coordinates. A stepper-driven belt positions a gantry carrying an SG90 servo. The servo pushes one selected pin at a time; its compliant feature deflects through the guide hole, expands and locks the pin in its raised state. Bolting the gantry to the pin frame maintains registration between commanded positions and physical pins.

Positioning and pushing are separate functions. The array provides 144 available positions, rather than 144 pins lifted together. The retained description does not establish the detailed axis arrangement, additional motor count or reset mechanism.

## Design iterations

Early pins caught or failed to rise. Revising the hollow pin, guide and locking interface together reduced the lift burden and improved retention through four prototype generations. Earlier references to a "clamp" describe this evolving mechanical interface, not a separate powered clamp lifting the pattern.

The roughly 60% early pin-rise failure and smooth final locking are qualitative observations from the retained project account. Fourteen demonstrated route patterns are reported, but no event-level denominator, repeat count or per-pin outcome log was retained. These functional demonstrations do not establish a measured reliability improvement, repeated-cycle durability or actuation force.

## CAD and build record

![early pin array test](images/early-pin-array-test.jpg)

![laser cut housing cad](images/laser-cut-housing-cad.png)

![sectioned custom pins](images/sectioned-custom-pins.png)

![custom pin cad dimension](images/custom-pin-cad-dimension.png)

[Full case study](https://www.mergenulziibayar.com/projects/v-aid-climbing) · [Engineering report](https://www.mergenulziibayar.com/downloads/reports/v-aid-climbing.pdf) · [Portfolio](https://www.mergenulziibayar.com)

## Record scope

This repository publishes the existing project photographs and CAD renders. [Image sources and hashes](sources.json) preserve their provenance. CAD renders are illustrations of the design record; native CAD files are not included. No new experiment was performed for this publication.

The engineering report retains its April 2026 cover date. The mechanism description was clarified by the owner on 13 November 2026; this later annotation supplies no new experimental result and does not change individual or team attribution.
