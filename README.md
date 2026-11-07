# Nexum FX
The Nexum effects engine as a separate mono/stereo mixer insert. 17 rack modules,
shared single-effect/chain library, growable macros and the family preset header.
This repository pins the canonical engine rather than maintaining a second copy.

```sh
git clone --recurse-submodules https://github.com/nexum-audio/nexum-fx.git
```
```powershell
cmake -S . -B build -G "Visual Studio 17 2022" -A x64
cmake --build build --config Release --target NexumFx_VST3 NexumFx_Standalone --parallel 1
```
Original implementation: AGPL-3.0-only; dependencies retain their licenses.
