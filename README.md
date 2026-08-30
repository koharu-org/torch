# Torch runtime for Koharu

Daily prebuilt [LibTorch](https://github.com/pytorch/pytorch) shared libraries and the `koharu-torch` shim for [Koharu](https://github.com/mayocream/koharu).

The release workflow resolves the latest stable PyTorch release and builds CPU, CUDA, HIP, and Metal variants for Windows, Linux, and macOS. It runs daily at 04:17 UTC, on pushes to `main`, and when started manually.

Build jobs use the `ubuntu-latest-xl`, `windows-latest-xl`, and `macos-latest-xl` GitHub-hosted larger runners.

Generated binaries are published through this repository's [releases](https://github.com/koharu-org/torch/releases).
