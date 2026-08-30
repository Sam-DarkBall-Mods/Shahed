# Shahed

[![CI](https://github.com/Sam-DarkBall-Mods/Shahed/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Shahed/actions/workflows/ci.yml)

The repository builds two PBOs. `lk_shahed` contains the Geran-2 and
Shahed-136 aircraft, their launcher trucks and the launch scripts.
`shahed228` contains the Shahed-238 variants and their trucks.

## Requirements

- Arma 3 2.22 or newer

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

Both old PBO names and prefixes are kept. The release archive contains
`lk_shahed.pbo` and `shahed228.pbo`.

## License

Code and configs use GPL-2.0-or-later. Original aircraft, vehicle and audio
assets use APL-SA. See [LICENSES.md](LICENSES.md).
