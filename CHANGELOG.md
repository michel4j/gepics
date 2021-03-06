# Changelog

## [2019.7.1] - 2019-05-16
### Changed
- Support Numpy array values when emitting "changed" signals
- Fixed GObject.idle_add deprecation  

## [2019.5.4] - 2019-05-16
### Changed
- Use EPICS Alarm Severity names for Alarm Enum NORMAL, MINOR, MAJOR, INVALID states 

## [2019.5.3] - 2019-05-13
### Changed
- Fixed issue where initial events were not being emitted. 

## [2019.5.2] - 2019-05-12
### Added
- Alarm Enum class with states NORMAL, WARNING, CRITICAL
- PV class now emits "alarm" signal with value corresponding to one of the Alarm states

## [2019.5.1] - 2019-05-11
### Added
- PV class now wraps pyepics.PV properly
- README now contains clear description of the project
- PV class emits "changed", "time" and "active" signals in response to channel access changes 