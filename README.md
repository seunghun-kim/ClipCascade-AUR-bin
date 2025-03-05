# ClipCascade for Arch Linux (AUR)

This repository provides a modified version of the [ClipCascade](https://github.com/Sathvik-Rao/ClipCascade) client (based on the `release/3.0.0` Linux GUI zip archive) tailored for seamless installation and operation on Arch Linux via the AUR (Arch User Repository). The codebase has been adjusted to ensure compatibility and error-free execution when installed through the AUR.

## Overview

ClipCascade is a lightweight tool designed for efficient clipboard sharing across devices. This fork adapts the original Linux GUI release for Arch Linux users by including a `PKGBUILD` file and minor code tweaks to resolve dependencies and runtime issues specific to the Arch ecosystem.

## Features

- Based on upstream `release/3.0.0` Linux GUI version.
- Optimized for Arch Linux with AUR support.

## Installation

- Install the package using your preferred AUR helper, e.g.:
    ```bash
    yay -S clipcascade-bin
    ```
    or
    ```bash
    paru -S clipcascade-bin
    ```

## Modifications from Upstream

- Adjusted file paths to resolve runtime errors observed on Arch systems. (709dbd7d)

## Usage

After installation, launch ClipCascade from your application menu.

Follow the on-screen instructions to configure clipboard sharing.

## Contributing

Feel free to submit issues or pull requests if you encounter bugs or have suggestions for improvements. This repository aims to maintain compatibility with Arch Linux while staying aligned with upstream updates.

## License

This project inherits the license from the upstream ClipCascade repository (see [upstream repo](https://github.com/Sathvik-Rao/ClipCascade) for details).

## Acknowledgments

- Original work by [Savith Rao](https://github.com/Sathvik-Rao).