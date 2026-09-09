## [v0.3.8](https://github.com/theforeman/puppet-foreman_scap_client/tree/v0.3.8) (2016-01-11)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/v0.3.7...v0.3.8)

- Support vintage ruby interpreters
- The command output shall go to /dev/null
- fix the documentation typo

## [v0.3.7](https://github.com/theforeman/puppet-foreman_scap_client/tree/v0.3.7) (2015-05-07)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/v0.3.6...v0.3.7)

- Support for content automated content fetching

## [v0.3.6](https://github.com/theforeman/puppet-foreman_scap_client/tree/v0.3.6) (2015-04-09)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/v0.3.5...v0.3.6)

- Support for subscription manager certificates

## [v0.3.5](https://github.com/theforeman/puppet-foreman_scap_client/tree/v0.3.5) (2015-03-03)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/v0.3.4...v0.3.5)

- port is now mandatory parameter

## [v0.3.4](https://github.com/theforeman/puppet-foreman_scap_client/tree/v0.3.4) (2015-02-26)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/v0.3.3...v0.3.4)

- bugfix package rubygem-foreman-scap-client installation

## [v0.3.3](https://github.com/theforeman/puppet-foreman_scap_client/tree/v0.3.3) (2015-02-09)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/0.3.2...v0.3.3)

- bugfixes foreman_scap_client.cfg template distribution

## [0.3.2](https://github.com/theforeman/puppet-foreman_scap_client/tree/0.3.2) (2015-01-15)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/0.3.1...0.3.2)

- new class foreman_scap_client introduced in body of puppet-openscap
- the puppet-openscap remains live in github.com/OpenSCAP/puppet-openscap

## [0.3.1](https://github.com/theforeman/puppet-foreman_scap_client/tree/0.3.1) (2014-07-25)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/0.3.0...0.3.1)

## [0.3.0](https://github.com/theforeman/puppet-foreman_scap_client/tree/0.3.0) (2014-07-25)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/0.2.0...0.3.0)

- All stored results are bzip2ed (~90% reduction of disc space)
- Module can upload results to Foreman's Smart Proxy
  (Assuming foreman-proxy_openscap plug-in installed).
- Support of Ruby 1.8 (previously 2.0+ was needed)
- Introduced resources:
  - scap_upload
- Introduced classes:
  - openscap::xccdf::foreman_audit

## [0.2.0](https://github.com/theforeman/puppet-foreman_scap_client/tree/0.2.0) (2014-07-16)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/0.1.0...0.2.0)

- the module attempts to install its dependencies
- introduced classes:
  - openscap
  - openscap::params
  - openscap::package
  - openscap::xccdf::eval

## [0.1.0](https://github.com/theforeman/puppet-foreman_scap_client/tree/0.1.0) (2014-06-05)

[Full Changelog](https://github.com/theforeman/puppet-foreman_scap_client/compare/d523ede483f4c060040108edfdcb91c1b737508f...0.1.0)

- project started
- introduced resources:
  - scap_schedule
  - xccdf_scan
