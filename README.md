Wine-Edge is a performance-oriented, up-to-date version built on pure Wine. It's a hobby project.

Added features:

Base: Vanilla Wine

Patches: wine-staging

Added features:

DXVK 2.7.1 (compiled with git version)

VKD3D-Proton 3.0.1 (compiled with git version)

D7VK (I didn't compile this, I used a ready-made build)

Wine-Mono 11.1.0
Wine-Gecko 2.47.4

Flags used during compilation: -03 -march=x86-64-v2, Polly flags.

I didn't use Polly when compiling DXVK/VKD3D, but I used LTO.
