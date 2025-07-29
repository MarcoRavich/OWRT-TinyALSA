# TinyALSA for OpenWRT

This repository builds TinyALSA (https://github.com/tinyalsa/tinyalsa) for OpenWRT using GitHub Actions.

## How it works

- Fetches upstream TinyALSA
- Downloads OpenWRT SDK/toolchain (change for your board/CPU)
- Builds tinycap, tinymix, etc. for OpenWRT
- Uploads binaries as GitHub Actions artifacts

## Customize

Edit `.github/workflows/build.yml` to change SDK/toolchain (CPU, OpenWRT version).

## Usage

Download the built artifacts from the Actions page after each build.