# Pocket Distro Alpha

A power-optimized Linux image for a CM5-based handheld with a Wayland touch UI and hot-swap peripheral modules.

## Project Goals

- Quantify and improve battery life vs. a stock Linux baseline
- Run a touch-capable Wayland UI on a portrait capacitive display
- Handle peripheral module attach/detach cleanly via a user-space daemon

## Hardware

Target: palm-sized CM5 handheld with USB-C PD peripheral slot.  
Development hardware available Term 1. Alpha hardware (EE team) expected late Summer 2026.

## Repo Structure

| Directory | Contents |
|---|---|
| `os/` | Kernel config, build system, cross-compilation |
| `ui/` | Wayland compositor and touch UI stack |
| `daemon/` | Hot-swap peripheral daemon |
| `power-measurement/` | Test harness, workloads, power reports |
| `docs/` | Architecture, handoff guides, EE integration notes |

## Sponsors

EPL — Ed Ivory, Ben Crall, Crow Crossman, Tucker Mastin

