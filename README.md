# prints

"Useful" everyday 3D-printable objects, modelled with OpenSCAD.

Dependencies:

- openscad
- bash
- coreutils

If you use Nix and direnv, everything is already set up properly for you.

Also included is [a tool](./bin/mkstl) for generating a nicely named STL from the SCAD files.


| objects                                | description                                                                                                                                           | notes                                                                                                                                                                                             |
| ---                                    | ---                                                                                                                                                   | ---                                                                                                                                                                                               |
| [Tongue scraper](./tonguescraper.scad) | A tongue scraper, clone of [this one](http://www.tonguescraperusa.com/Oolitt-Tongue-Cleaner--Normal-Use-Pkg-of-6-_p_3.html). Useful for oral hygiene. | Adjust layerheight until your slicer slices it as a single layer. Multiple layers create crevasses that can harbor bacteria. Print at your own risk, preferably with PETG and a non-brass nozzle. |
