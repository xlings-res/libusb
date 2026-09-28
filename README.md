# libusb

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/l/libusb.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/libusb-1.0.29-h73b1eb8_0.conda | `89c84f5b26028a9d0f5c4014330703e7dff73ba0c98f90103e9cef6b43a5323c` | conda-forge libusb 1.0.29 h73b1eb8_0 (LGPL-2.1-or-later) |

## Command

```
.agents/tools/repack/repack.py \
    --name libusb \
    --version 1.0.29 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/libusb-1.0.29-h73b1eb8_0.conda#89c84f5b26028a9d0f5c4014330703e7dff73ba0c98f90103e9cef6b43a5323c \
    --require lib/libusb-1.0.so.0
```

