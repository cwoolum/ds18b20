# Changelog

## [2.0.0] - 2026-05-02

### Changed

- Updated to `embedded-hal` 1.0 (breaking change from 0.2.x)
- Replaced `embedded_hal::blocking::delay::DelayUs<u16>` with `embedded_hal::delay::DelayNs`
- Replaced `embedded_hal::blocking::delay::DelayMs<u16>` with `embedded_hal::delay::DelayNs`
- Replaced `embedded_hal::digital::v2::{InputPin, OutputPin}` with `embedded_hal::digital::{InputPin, OutputPin}`
- Updated `one-wire-bus` dependency to `cwoolum/one-wire-bus` v2.0.0 (embedded-hal 1.0 compatible fork)
- `Resolution::max_measurement_time_millis` now returns `u32` instead of `u16`
- Updated `Cargo.toml` edition to 2021
- Repository updated to `https://github.com/cwoolum/ds18b20`
