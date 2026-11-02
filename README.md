# StatusOS

StatusOS is an experimental x86_64 operating system being developed from scratch in Rust.

The initial development target is QEMU with UEFI firmware. The project prioritizes a reliable, maintainable kernel foundation, with each milestone compiled and tested before additional subsystems are introduced.

## Current status

The kernel currently compiles for x86_64 bare metal. Bootloader integration, serial diagnostics, and QEMU boot testing are still in progress.

## Development environment

- Windows 11
- Rust stable
- QEMU
- PowerShell

## Build

```powershell
cargo build --release --target x86_64-unknown-none