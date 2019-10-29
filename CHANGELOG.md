# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.19.0] - 2019-10-28
### Added
- CHANGELOG
- `get_device_stat()` method to get current state & configuration of device
- `get_switch_port_overrides()` method to retrieve the overrides applied to the given Switch
- `switch_port_power_off()` to turn off PoE for a specific Switch Port
- `switch_port_power_on()` to turn on PoE for a specific Switch Port
- Namespaced logger support
### Fixed
- Pinned version of `requests` to better protect against future dependency issues