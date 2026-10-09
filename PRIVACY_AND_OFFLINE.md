# Privacy and Offline Behavior

REAL.LIFE Public Demo is designed to run offline.

## Network

- No account is required.
- No LLM or paid API is required.
- The game does not need a persistent internet connection.
- The candidate does not implement analytics, advertising, cloud saves, multiplayer or telemetry.

## Local files

The game writes only normal local runtime data, including:

- the player save and backup;
- local settings such as audio level, mute, fullscreen and first-day-guide visibility;
- screenshots only when the player explicitly invokes the screenshot command.

Files are stored in the Godot user-data location for the operating system. Removing that folder removes the local demo save/settings.

## Development and distribution

GitHub Actions is used by the private development repository to build and test release candidates. That build infrastructure is separate from the shipped game and is not contacted by the runtime.

## Future changes

If analytics, online accounts, cloud saves or multiplayer are ever introduced, this document and the in-game disclosure must be updated before those features ship.
