# GNS3 GUI flatpak

This repository contains all packaging information and Github Action pipelines to build a flatpak.

## Build
This command builds the flatpak and installs it on your system

`flatpak-builder --force-clean --user --install-deps-from=flathub --repo=repo --install builddir com.gns3.GNS3.yml`

## Run
And to run the installed flatpak execute:

`flatpak run com.gns3.GNS3`