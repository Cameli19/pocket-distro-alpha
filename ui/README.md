# Daemon — Hot-Swap Peripheral Manager

User-space daemon that handles peripheral module attach and detach events.

## Goals

- Detect module attach/detach via udev or similar
- Maintain a registry of known module types
- Invoke mount/cleanup logic on state changes
- Notify the UI layer of current module state
- Handle unclean detach without data loss or system instability