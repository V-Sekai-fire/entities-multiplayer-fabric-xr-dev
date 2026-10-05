# entities-multiplayer-fabric-xr-dev

A superproject that pins the engine fork, the XR interaction addon, its test project and the libraries, proofs and projects around them as submodules.

## What it is for

Each submodule is its own repository; this one records which of their revisions work together. `.gitmodules` names every submodule and its path.

## Build and run

    git submodule update --init --recursive

Then build the engine in its submodule, `opentelemetry-godot`, as that repository describes.

## Licence

The licence is not stated; each submodule carries its own.
