# Khalid Abdulmahsen

I build Go systems tools for Linux internals, protocol decoding, and network observability.
My projects turn kernel counters and network telemetry into inspectable state and terminal interfaces.

## Featured systems projects

| Project | Architecture and technical focus | Stack | Release |
| --- | --- | --- | --- |
| [sdr-aircraft-tracker](https://github.com/khalid7344/sdr-aircraft-tracker) | Mode S DF17 decoder, CRC-24 parity validation, global CPR coordinates, and aircraft tracking TUI. | Go · TCP/AVR · RTL-SDR front end | [v1.0.1](https://github.com/khalid7344/sdr-aircraft-tracker/releases/tag/v1.0.1) |
| [pulse-linux-observatory](https://github.com/khalid7344/pulse-linux-observatory) | Linux `/proc` engine with `(PID, StartTime)` identity, two-sample CPU deltas, PSS/RSS accounting, and sustained alerts. | Go · Linux /proc · Bubble Tea | [v1.0.0](https://github.com/khalid7344/pulse-linux-observatory/releases/tag/v1.0.0) |
| [home-network-watch](https://github.com/khalid7344/home-network-watch) | Pi-hole DNS and WireGuard telemetry, baseline anomaly rules, and embedded SQLite persistence. | Go · WireGuard · Pi-hole · SQLite | [v1.0.1](https://github.com/khalid7344/home-network-watch/releases/tag/v1.0.1) |

## Technical focus and toolchain

**Languages and core:** Go (concurrency, standard library, CGO-free binaries) · Python · SQL · POSIX shell

**Systems and networking:** Linux kernel interfaces (`/proc`, sysfs) · TCP/IP and UDP sockets · DNS and WireGuard telemetry · RTL-SDR / ADS-B (1090 MHz Mode S)

**Environment and practices:** Pop!_OS Linux · QEMU/KVM · Git and GitHub Actions CI · Race-tested, table-driven tests
