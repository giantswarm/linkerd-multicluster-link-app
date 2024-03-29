# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.11.1] - 2023-12-13

### Changed

- Configure `gsoci.azurecr.io` as the default container image registry.

## [0.11.0] - 2023-06-15

### Changed

- Replace icon and add logo.
- Upgrade Linkerd to v2.13.4.

## [0.10.0] - 2023-03-09

### Changed

- Upgrade linkerd to v2.12.4.
- Update icon URL in `Chart.yaml` to self-hosted.

## [0.9.0] - 2022-11-07

### Changed

- Upgrade to 2.12.2 ([#20](https://github.com/giantswarm/linkerd2-multicluster-link-app/pull/20).
- Add image registry switch to automatically switch the used image registry based on the installation region.

## [0.8.0] - 2022-09-21

### Changed

Upgrade app version to 2.11.4.

## [0.7.2] - 2022-08-16

- Make service account configurable.

## [0.7.1] - 2022-08-04

### Changed

- Encode in base64 the CA on the kubeconfig link.

## [0.7.0] - 2022-07-14

- Add first version of the Linkerd multicluster link chart.

[Unreleased]: https://github.com/giantswarm/linkerd-multicluster-link-app/compare/v0.11.1...HEAD
[0.11.1]: https://github.com/giantswarm/linkerd-multicluster-link-app/compare/v0.11.0...v0.11.1
[0.11.0]: https://github.com/giantswarm/linkerd-multicluster-link-app/compare/v0.10.0...v0.11.0
[0.10.0]: https://github.com/giantswarm/linkerd-multicluster-link-app/compare/v0.9.0...v0.10.0
[0.9.0]: https://github.com/giantswarm/linkerd-multicluster-link-app/compare/v0.8.0...v0.9.0
[0.8.0]: https://github.com/giantswarm/linkerd2-multicluster-link-app/compare/v0.7.2...v0.8.0
[0.7.2]: https://github.com/giantswarm/linkerd2-multicluster-link-app/compare/v0.7.1...v0.7.2
[0.7.1]: https://github.com/giantswarm/linkerd2-multicluster-link-app/compare/v0.7.0...v0.7.1
[0.7.0]: https://github.com/giantswarm/linkerd2-multicluster-link-app/compare/v0.7.0...v0.7.0
