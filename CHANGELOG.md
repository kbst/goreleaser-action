# Changelog

## 2.2.0 (2020/08/27)

* Use GITHUB_REF to retrieve tag before checking the most recent tag (#238)
* Update deps

## 2.1.1 (2020/06/24)

* Fix workdir (#224)

## 2.1.0 (2020/06/15)

* Implement (optional) semver parsing of version (#213)
* Remove unshallow step (goreleaser/goreleaser#1608)

## 2.0.2 (2020/05/10)

* Use template in `sign.args`

## 2.0.1 (2020/05/10)

* Dummy release to mark v2 as latest on the marketplace

## 2.0.0 (2020/05/10)

* Remove `key` input and use [Import GPG](https://github.com/crazy-max/ghaction-import-gpg) GitHub Action instead.
* Make `args` input as required
* Go 1.14
* Update deps

## 1.5.1 (2020/05/10)

* Mark `key` input as deprecated

## 1.5.0 (2020/05/07)

* Use native GitHub Action tools to download assets and use GitHub API
* Fix unexpected output when tag not found
* Use GitHub Action exec
* Cleanup local paths from extra fields
* Add notes about limitation with GITHUB_TOKEN (#58)
* Add Codecov

## 1.4.0 (2020/04/09)

* Use ncc and clean workflows
* Update deps

## 1.3.1 (2020/02/14)

* Don't fail on `getTag` (#98)

## 1.3.0 (2020/02/11)

* Improve git tag detection (#77)
* Only handle snapshot flag for release cmd (#94)
* Use `core.info` instead of `console.log`
* Update deps
* Update gitattributes

## 1.2.1 (2020/01/20)

* Update deps

## 1.2.0 (2019/12/24)

* Update deps

## 1.1.0 (2019/12/02)

* Add input to run GoReleaser from a subdirectory (#45)

## 1.0.2 (2019/11/14)

* Fix tsc gen

## 1.0.1 (2019/11/14)

* Update deps

## 1.0.0 (2019/10/04)

* Stable release
* Update deps

## 0.4.0 (2019/09/28)

* Move repository to GoReleaser org (#3)

## 0.3.0 (2019/09/26)

* Artifact signing (#2)

## 0.2.1 (2019/09/22)

* Typo

## 0.2.0 (2019/09/20)

* Snapshot forced if no tag found

## 0.1.0 (2019/09/20)

* Initial version
