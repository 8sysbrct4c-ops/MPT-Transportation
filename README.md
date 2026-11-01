# MPT Transportation

A Minecraft Bedrock Edition public-transportation add-on project.

## Project status

**Early development scaffold — not yet a finished or tested add-on.** This repository contains the initial pack structure and design notes. It does not yet provide a complete downloadable `.mcaddon`.

## Planned features

- Rideable city buses with passenger seats.
- Exterior destination displays showing route number and destination.
- Interior passenger information screen (infoskärm) showing the line, destination, next stop and following stop.
- Named bus stops, shelters and terminals with departure boards.
- Route progression, stop announcements, stop requests and door animations.
- Later transport types: trams, trains, metro, articulated buses and double-deckers.

## Target version

Minecraft Bedrock Edition **26.52** (target; compatibility has not yet been verified in-game).

## Custom routes

Six editable example bus lines (1–6) are defined in `config/routes.json`. See `docs/CUSTOM_ROUTES.md` to change numbers, destinations, colours and stop lists.

## Pack layout

- `behavior_pack/` — entity behavior, spawn rules and gameplay data.
- `resource_pack/` — entity geometry, materials, textures and visual assets.
- `docs/` — feature plan and development notes.

## Installation

There is no installable release yet. When a tested build is available, it will be published under GitHub Releases as an `.mcaddon` file.

## Development

Contributions and bug reports are welcome. Please include your Minecraft version, device/platform, steps to reproduce and any content-log errors.

## License

A license has not been selected yet.