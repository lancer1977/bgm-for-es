# Repository State

- Type: Python service/package
- Package: `bgm`
- Entry point: `startbgm = bgm:main`
- Validation: `./scripts/validate.sh`
- CI: `.github/workflows/validate.yml`

Current validation covers unit tests for the music state machine. Runtime
behavior still needs a RetroPie-style host with pygame and EmulationStation.
