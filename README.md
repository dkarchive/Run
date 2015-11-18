# Run

[ReadmeCritic](https://github.com/pulls?utf8=✓&q=is%3Amerged+is%3Apr+author%3AReadmeCritic) uses [`frankenstein`](https://github.com/dkhamsing/frankenstein) to correct [HTTP redirects](https://en.wikipedia.org/wiki/URL_redirection) in GitHub READMEs.

Examples

- https://github.com/mesosphere/marathon/pull/2649
- https://github.com/adametry/gulp-eslint/pull/119
- https://github.com/twbs/bootstrap-sass/pull/984
- and [more](https://github.com/pulls?utf8=✓&q=is%3Amerged+is%3Apr+author%3AReadmeCritic)

To get ReadmeCritic to run and check for redirected URLs, open [an issue here](https://github.com/ReadmeCritic/Run/issues/new) :runner: 

The issue will be updated with results (if redirects are found).

## Issue Format

### `Run` once

Open an issue with the `repo` in the issue `Title`.

```
Title: fastlane/deliver
Title: https://github.com/fastlane/deliver
```

### `Run` multiple

Open an issue with the `repos` in the issue `Comment` ([example](https://github.com/ReadmeCritic/Run/issues/4)).

```shell
Title: run # can be anything
Comment: 
fastlane/deliver
orta/ARAnalytics
```

To check all projects from a GitHub user / organisation, open an issue with @username in the issue `Title`.

```
Title: @dkhamsing
Title: @CocoaPods
```

⚠️ @username is not supported yet :grin:

## Contact

- [github.com/dkhamsing](https://github.com/dkhamsing)
- [twitter.com/dkhamsing](https://twitter.com/dkhamsing)
