# release-plan Changelog

## Release (2024-07-11)

release-plan 0.9.1 (patch)

#### :bug: Bug Fix
* `release-plan`
  * [#72](https://github.com/embroider-build/release-plan/pull/72) add a test to exercise latest-version dependency and update it ([@mansona](https://github.com/mansona))

#### :memo: Documentation
* `release-plan`
  * [#58](https://github.com/embroider-build/release-plan/pull/58) Update readme ([@NullVoxPopuli](https://github.com/NullVoxPopuli))

#### Committers: 2
- Chris Manson ([@mansona](https://github.com/mansona))
- [@NullVoxPopuli](https://github.com/NullVoxPopuli)

## Release (2024-03-12)

release-plan 0.9.0 (minor)

#### :rocket: Enhancement
* `release-plan`
  * [#66](https://github.com/embroider-build/release-plan/pull/66) start using github-changelog ([@mansona](https://github.com/mansona))

#### :house: Internal
* `release-plan`
  * [#67](https://github.com/embroider-build/release-plan/pull/67) fix typo in release-plan setup ([@mansona](https://github.com/mansona))
  * [#64](https://github.com/embroider-build/release-plan/pull/64) update release-plan-setup ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))

## Release (2024-02-16)

release-plan 0.8.0 (minor)

#### :rocket: Enhancement
* `release-plan`
  * [#56](https://github.com/embroider-build/release-plan/pull/56) add the default github-changelog unlabelled section name to parser ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))

## Release (2024-02-14)

release-plan 0.7.1 (patch)

#### :bug: Bug Fix
* `release-plan`
  * [#54](https://github.com/embroider-build/release-plan/pull/54) fix import of semver ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))

## Release (2024-01-26)

release-plan 0.7.0 (minor)

#### :rocket: Enhancement
* `release-plan`
  * [#52](https://github.com/embroider-build/release-plan/pull/52) add ability to pass tag to publish command ([@mansona](https://github.com/mansona))

#### :bug: Bug Fix
* `release-plan`
  * [#51](https://github.com/embroider-build/release-plan/pull/51) Make changelog header discovery more forgiving (case-insensitive) ([@mansona](https://github.com/mansona))

#### :house: Internal
* `release-plan`
  * [#49](https://github.com/embroider-build/release-plan/pull/49) add a basic test for updateChangelog ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
## Release (2024-01-24)

release-plan 0.6.1 (patch)

#### :bug: Bug Fix
* `release-plan`
  * [#47](https://github.com/embroider-build/release-plan/pull/47) Robustly discover packages with @manypkg ([@NullVoxPopuli](https://github.com/NullVoxPopuli))

#### Committers: 1
- [@NullVoxPopuli](https://github.com/NullVoxPopuli)
## Release (2023-12-13)

release-plan 0.6.0 (minor)

#### :rocket: Enhancement
* `release-plan`
  * [#38](https://github.com/embroider-build/release-plan/pull/38) add --publish-branch if passed to release-plan publish ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
## Release (2023-12-06)

release-plan 0.5.1 (patch)

#### :bug: Bug Fix
* `release-plan`
  * [#35](https://github.com/embroider-build/release-plan/pull/35) fix pnpm package discovery bug ([@mansona](https://github.com/mansona))
  * [#34](https://github.com/embroider-build/release-plan/pull/34) Fix pnpm package discovery ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
## Release (2023-12-06)

release-plan 0.5.0 (minor)

#### :rocket: Enhancement
* `release-plan`
  * [#32](https://github.com/embroider-build/release-plan/pull/32) update lerna-changelog ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
## Release (2023-12-04)

release-plan 0.4.1 (patch)

#### :bug: Bug Fix
* [#30](https://github.com/embroider-build/release-plan/pull/30) add shebang back and fix linting config ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
## Release (2023-12-04)

release-plan 0.4.0 (minor)

#### :rocket: Enhancement
* [#28](https://github.com/embroider-build/release-plan/pull/28) pick the correct package manager to do npm publish ([@mansona](https://github.com/mansona))

#### :house: Internal
* [#29](https://github.com/embroider-build/release-plan/pull/29) Add linting and check it in CI  ([@mansona](https://github.com/mansona))
* [#27](https://github.com/embroider-build/release-plan/pull/27) run npm init release-plan-setup --update ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
## Release (2023-11-24)

release-plan 0.3.0 (minor)

#### :rocket: Enhancement
* [#24](https://github.com/embroider-build/release-plan/pull/24) add support for npm workspaces ([@mansona](https://github.com/mansona))

#### :bug: Bug Fix
* [#23](https://github.com/embroider-build/release-plan/pull/23) use require.resolve to find lerna-changelog ([@mansona](https://github.com/mansona))
* [#21](https://github.com/embroider-build/release-plan/pull/21) don't throw when we encounter an unknown package ([@mansona](https://github.com/mansona))
* [#20](https://github.com/embroider-build/release-plan/pull/20) fix updating changelog ([@mansona](https://github.com/mansona))

#### :house: Internal
* [#25](https://github.com/embroider-build/release-plan/pull/25) remove reference to @embroider ([@mansona](https://github.com/mansona))
* [#22](https://github.com/embroider-build/release-plan/pull/22) remove unused package.json ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))

## Release (2023-11-23)

release-plan 0.2.3 (patch)

#### :memo: Documentation
* [#17](https://github.com/embroider-build/release-plan/pull/17) add a basic readme ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))

## Release (2023-11-23)

release-plan 0.2.2 (patch)

#### :bug: Bug Fix
* [#15](https://github.com/embroider-build/release-plan/pull/15) actually use otp when it's provided ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
## Release (2023-11-23)

release-plan 0.2.1 (patch)

#### :bug: Bug Fix
* [#13](https://github.com/embroider-build/release-plan/pull/13) Fix npm publish ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
## Release (2023-11-23)

release-plan 0.2.0 (minor)

#### :rocket: Enhancement
* [#11](https://github.com/embroider-build/release-plan/pull/11) Fix publish step ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
## Release (2023-11-20)

release-plan 0.1.0 (minor)

#### :rocket: Enhancement
* [#5](https://github.com/embroider-build/release-plan/pull/5) add --single-package option ([@mansona](https://github.com/mansona))
* [#1](https://github.com/embroider-build/release-plan/pull/1) use tsup ([@mansona](https://github.com/mansona))

#### :house: Internal
* [#7](https://github.com/embroider-build/release-plan/pull/7) use dist/cli.js directly in workflows ([@mansona](https://github.com/mansona))
* [#6](https://github.com/embroider-build/release-plan/pull/6) add workflows for review and release ([@mansona](https://github.com/mansona))
* [#4](https://github.com/embroider-build/release-plan/pull/4) reset version so release-plan will work on itself ([@mansona](https://github.com/mansona))
* [#3](https://github.com/embroider-build/release-plan/pull/3) convert everything to work correctly with ESM ([@mansona](https://github.com/mansona))
* [#2](https://github.com/embroider-build/release-plan/pull/2) revert back from tsup to tsc ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))
