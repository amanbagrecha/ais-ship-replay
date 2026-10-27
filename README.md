# Ship Replay 3D

A 3D replay of one day of AIS ship traffic in a US port. Ships are drawn as 3D
models on a tilted map with their tracks, and a timeline at the bottom plays the
day back at 1×–1200× with sunset and sunrise marked. Click any ship to ride along
with it; the side panel lets you pick a port and shows details for the selected
vessel.

Position reports come from NOAA / BOEM via
[MarineCadastre.gov](https://marinecadastre.gov/ais/) and are read live from the
public Fused H3 index, one map tile at a time. There is no Python and no local
data: the app is a single `index.html`.
