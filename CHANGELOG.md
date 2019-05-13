# Changelog

## [2019.5.2] - 2019-05-12
### Added
- Alarm Enum class with states NORMAL, WARNING, CRITICAL
- PV class now emits "alarm" signal with value corresponding to one of the Alarm states

## [2019.5.1] - 2019-05-11
### Added
- PV class now wraps pyepics.PV properly
- README now contains clear description of the project
- PV class emits "changed", "time" and "active" signals in response to channel access changes 