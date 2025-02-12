# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
## [0.11.0] - 2022-04-04
### Added
- Adds a new Matlab default version of 2022a

## [0.10.0] - 2021-12-10
### Added
- [15](https://github.com/OSC/bc_osc_matlab/pull/15)
  - Enabled the Pitzer Cluster in Matlab along with the related selection configurations.
  - Migrated all select functionality to the new Dynamic JS select functionality.

## [0.9.0] - 2021-01-20
### Added
- [13](https://github.com/OSC/bc_osc_matlab/pull/13)
  - removed owens-slurm and torque related configurations
  - changed account to be a select widget with only valid groups as options

## [0.8.0] - 2020-11-18
### Added
- Added owens-slurm cluster to being migrating Owens to Slurm in
  [11](https://github.com/OSC/bc_osc_matlab/pull/11)

## [0.7.0] - 2019-12-10
### Added
- Adds a new Matlab default version of 2019b

## [0.6.1] - 2019-07-09
### Added
- Added xalt

## [0.6.0]
### Added
- Adds a new Matlab default version of 2018b

## [0.5.1]
### Fixed
- Fixed front end to allow ppn control to remain blank

## [0.5.0]
### Added
- Added control to select number of CPUs

## [0.4.0]
### Added
- Added MATLAB version 2018a.

## [0.3.0] - 2018-04-19
### Changed
- Switched from using Fluxbox to Xfce for the window manager.

### Fixed
- Fixed local configuration not always being ignored.

## [0.2.0] - 2018-02-26
### Added
- Added MATLAB versions R2017a and R2015b.
- Added hardware rendering support.
  [#3](https://github.com/OSC/bc_osc_matlab/issues/3)

### Changed
- Modified the `CHANGELOG.md` formatting.
- Refactored to use new Dashboard ERB templating.
  [#6](https://github.com/OSC/bc_osc_matlab/issues/6)
- Updated date in `LICENSE.txt`.

## [0.1.0] - 2017-06-14
### Changed
- Refactored for the new Batch Connect app.

## [0.0.4] - 2017-05-15
### Changed
- Remove FVWM and added Fluxbox as the window manager.

## [0.0.3] - 2017-04-24
### Changed
- Version the assets.

### Removed
- Remove `bin/setup` as not necessary anymore.

## [0.0.2] - 2017-04-21
### Added
- Added `bin/setup` script for easier deployment.

## 0.0.1 - 2017-04-04
### Added
- Initial release!

[Unreleased]:
https://github.com/OSC/bc_osc_matlab/compare/v0.11.0...HEAD
[0.11.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.10.0...v0.11.0
[0.10.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.9.0...v0.10.0
[0.9.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.8.0...v0.9.0
[0.8.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.7.0...v0.8.0
[0.7.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.6.1...v0.7.0
[0.6.1]: https://github.com/OSC/bc_osc_matlab/compare/v0.6.0...v0.6.1
[0.6.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.5.1...v0.6.0
[0.5.1]: https://github.com/OSC/bc_osc_matlab/compare/v0.5.0...v0.5.1
[0.5.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/OSC/bc_osc_matlab/compare/v0.0.4...v0.1.0
[0.0.4]: https://github.com/OSC/bc_osc_matlab/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/OSC/bc_osc_matlab/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/OSC/bc_osc_matlab/compare/v0.0.1...v0.0.2
