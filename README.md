# Torch runtime for Koharu

Weekly prebuilt [LibTorch](https://github.com/pytorch/pytorch) shared libraries and the `koharu-torch` shim for [Koharu](https://github.com/mayocream/koharu).

The release workflow resolves the latest stable PyTorch release and builds CPU, CUDA, HIP, and Metal variants for Windows, Linux, and macOS. It runs every Sunday at 04:17 UTC and can also be started manually.

Build jobs use the `ubuntu-latest-xlarge`, `windows-latest-xlarge`, and `macos-latest-xlarge` GitHub-hosted larger runners.

Generated binaries are published through this repository's [releases](https://github.com/koharu-org/torch/releases).
