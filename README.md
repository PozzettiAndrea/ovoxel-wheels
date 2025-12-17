# O-Voxel Pre-built Wheels

Pre-compiled CUDA wheels for [O-Voxel](https://github.com/microsoft/TRELLIS.2/tree/main/o-voxel) - O-Voxel representation library for converting between textured meshes and sparse voxel structures.

## Installation

```bash
pip install o_voxel --find-links https://PozzettiAndrea.github.io/ovoxel-wheels/
```

## Supported Configurations

- **CUDA:** 12.4, 12.8
- **Python:** 3.10, 3.11, 3.12
- **Platforms:** Linux (x86_64), Windows (amd64)
- **GPU:** RTX 20/30/40 series (SM 7.5+)

## Building

Wheels are automatically built via GitHub Actions on push to main. To trigger a manual build:

1. Go to Actions tab
2. Select the workflow for the CUDA version you want
3. Click "Run workflow"

## License

The wheel build scripts are MIT licensed. O-Voxel retains its original license from [microsoft/TRELLIS.2](https://github.com/microsoft/TRELLIS.2).
