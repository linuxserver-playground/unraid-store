# LinuxServer.io Unraid templates

**This repository is generated.** Every file is written by the [hub](https://github.com/linuxserver-playground/hub) from each image's `image.yml`
and newest build, and pushed by its deploy workflow; edits here are overwritten by the next run. Changes belong in
the image's repository (its `image.yml`) or in the hub's `lsio_hub/generate/unraid.py`.

## Import

Community Applications lists template repositories once its moderators have added them. Until this one is, copy an image's XML into `/boot/config/plugins/dockerMan/templates-user/` on the flash drive and pick it under *Docker*, *Add Container*, *Template*. Each template's `TemplateURL` points back here, so Unraid picks up changes.

## Layout

One `<image>.xml` per image at the root, deprecated images in `deprecated/`, and `ignore.list` for images that opt out of Unraid.

The same output is served at `https://linuxserver-playground.github.io/hub/stores/unraid/`; the store index
with every platform is `https://linuxserver-playground.github.io/hub/api/v1/stores/index.json`.
