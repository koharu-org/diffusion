# Diffusion runtime for Koharu

Daily prebuilt [stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp) shared libraries for [Koharu](https://github.com/mayocream/koharu).

The release workflow resolves the latest stable upstream release and builds CUDA, HIP, Vulkan, and Metal variants for Windows, Linux, and macOS. It runs daily at 03:47 UTC, on pushes to `main`, and when started manually.

Build jobs use the standard `ubuntu-latest`, `windows-2022`, and `macos-latest` GitHub-hosted runners.

Generated binaries are published through this repository's [releases](https://github.com/koharu-org/diffusion/releases).
