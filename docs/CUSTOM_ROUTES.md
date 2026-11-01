# Custom bus lines 1–6

The six starter bus lines are stored in `config/routes.json`.

## Change a line

For each route, edit:

- `line_number`: the number shown on the bus.
- `destination`: the destination name.
- `display_text`: the complete text intended for the exterior display.
- `color`: route colour as a hex colour.
- `stops`: ordered list of station/stop names. The final item is the destination.

You can change the names and stops to anything you want. Keep each route's `id` unique and keep `line_number` values unique if you want six separate lines.

## Starter lines

| Line | Example destination |
|---|---|
| 1 | Centralstationen |
| 2 | Sjukhuset |
| 3 | Hamnterminalen |
| 4 | Universitetet |
| 5 | Flygplatsen |
| 6 | Äventyrsbadet |

These are example Swedish-style route names, not real Västtrafik services.

## Current implementation status

This is the editable route-data layer. It does not yet automatically drive the bus displays or move the bus between stops. That requires the next Bedrock Script API and resource-pack implementation step, followed by in-game testing on Bedrock 26.52.
