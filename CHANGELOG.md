# Changelog

<!-- markdownlint-disable no-duplicate-header -->

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

------

## [Unreleased]

### Added

- Add question/help/support issue template [@Benjamin-eecs](https://github.com/Benjamin-eecs) in [#43](https://github.com/metaopt/TorchOpt/pull/43).
- Add parallel training on one GPU using functorch.vmap example [@Benjamin-eecs](https://github.com/Benjamin-eecs) in [#32](https://github.com/metaopt/TorchOpt/pull/32).


### Changed

- Update image link in README to support pypi rendering [@Benjamin-eecs](https://github.com/Benjamin-eecs) in [#56](https://github.com/metaopt/TorchOpt/pull/56).

### Fixed

- Fix momentum tracing by [@XuehaiPan](https://github.com/XuehaiPan) in [#58](https://github.com/metaopt/TorchOpt/pull/58).
- Fix CUDA build for accelerated OP [@XuehaiPan](https://github.com/XuehaiPan) in [#53](https://github.com/metaopt/TorchOpt/pull/53).
- Fix gamma error in MAML-RL implementation [@Benjamin-eecs](https://github.com/Benjamin-eecs) [#47](https://github.com/metaopt/TorchOpt/pull/47).

### Removed

------

## [0.4.3] - 2022-08-08

### Added

- Bump PyTorch version to 1.12.1 by [@XuehaiPan](https://github.com/XuehaiPan) in [#49](https://github.com/metaopt/TorchOpt/pull/49).
- CPU-only build without `nvcc` requirement by [@XuehaiPan](https://github.com/XuehaiPan) in [#51](https://github.com/metaopt/TorchOpt/pull/51).
- Use [`cibuildwheel`](https://github.com/pypa/cibuildwheel) to build wheels by [@XuehaiPan](https://github.com/XuehaiPan) in [#45](https://github.com/metaopt/TorchOpt/pull/45).
- Use dynamic process number in CPU kernels by [@JieRen98](https://github.com/JieRen98) in [#42](https://github.com/metaopt/TorchOpt/pull/42).

### Changed

- Use correct Python Ctype for pybind11 function prototype [@XuehaiPan](https://github.com/XuehaiPan) in [#52](https://github.com/metaopt/TorchOpt/pull/52).

------

## [0.4.2] - 2022-07-26

### Added

- Read the Docs integration by [@Benjamin-eecs](https://github.com/Benjamin-eecs) and [@XuehaiPan](https://github.com/XuehaiPan) in [#34](https://github.com/metaopt/TorchOpt/pull/34).
- Update documentation and code styles by [@Benjamin-eecs](https://github.com/Benjamin-eecs) and [@XuehaiPan](https://github.com/XuehaiPan) in [#22](https://github.com/metaopt/TorchOpt/pull/22).
- Update tutorial notebooks by [@XuehaiPan](https://github.com/XuehaiPan) in [#27](https://github.com/metaopt/TorchOpt/pull/27).
- Bump PyTorch version to 1.12 by [@XuehaiPan](https://github.com/XuehaiPan) in [#25](https://github.com/metaopt/TorchOpt/pull/25).
- Support custom Python executable path in `CMakeLists.txt` by [@XuehaiPan](https://github.com/XuehaiPan) in [#18](https://github.com/metaopt/TorchOpt/pull/18).
- Add citation information by [@waterhorse1](https://github.com/waterhorse1) in [#14](https://github.com/metaopt/TorchOpt/pull/14) and [@Benjamin-eecs](https://github.com/Benjamin-eecs) in [#15](https://github.com/metaopt/TorchOpt/pull/15).
- Implement RMSProp optimizer by [@future-xy](https://github.com/future-xy) in [#8](https://github.com/metaopt/TorchOpt/pull/8).

### Changed

- Use `pyproject.toml` for packaging and update GitHub Action workflows by [@XuehaiPan](https://github.com/XuehaiPan) in [#31](https://github.com/metaopt/TorchOpt/pull/31).
- Rename the package from `TorchOpt` to `torchopt` by [@XuehaiPan](https://github.com/XuehaiPan) in [#20](https://github.com/metaopt/TorchOpt/pull/20).

### Fixed

- Fixed errors while building from the source and add `conda` environment recipe by [@XuehaiPan](https://github.com/XuehaiPan) in [#24](https://github.com/metaopt/TorchOpt/pull/24).

------

## [0.4.1] - 2022-04-15

### Fixed

- Fix set devices bug for multi-GPUs.

------

## [0.4.0] - 2022-04-09

### Added

- The first beta release of TorchOpt.
- TorchOpt with L2R, LOLA, MAML-RL, MGRL, and few-shot examples.

------

[Unreleased]: https://github.com/olivierlacan/keep-a-changelog/compare/v0.4.3...HEAD
[0.4.3]: https://github.com/olivierlacan/keep-a-changelog/compare/v0.4.2...v0.4.3
[0.4.2]: https://github.com/olivierlacan/keep-a-changelog/compare/v0.4.1...v0.4.2
[0.4.1]: https://github.com/olivierlacan/keep-a-changelog/compare/v0.4.0...v0.4.1
[0.4.0]: https://github.com/olivierlacan/keep-a-changelog/releases/tag/v0.4.0