diff-match-patch
================

[![Generated by attribution][attribution-badge]][attribution-url]


v20241021
---------

Bugfix release

- Stop breaking surrogate pairs in `toDelta()` (#17)
- Start tracking new upstream https://github.com/dmsnell/diff-match-patch (#17)
- Removed `imp` usage in speedtest
- Updated dev dependencies, use uv for dev workflows when available (#22)
- Tested on Python 3.8-3.13
- Untested on Python 3.7, will be unsupported in future release

```text
$ git shortlog -s v20230430...v20241021
     7	Amethyst Reese
     5	dependabot[bot]
     5	matthewhegarty
```


v20230430
---------

Maintenance release

- Replaced deprecated `imp` usage with `importlib` (#7)
- Migrated to PEP 621 metadata, flit
- Reformated with updated black/µsort/µfmt
- Tested on Python 3.7 - 3.11
- Dropped support for Python 2.7, 3.5, and 3.6

```text
$ git shortlog -s v20200713...v20230430
    14	Amethyst Reese
     1	dependabot[bot]
```


v20200713
---------

Maintenance release

- Pulls in upstream change to use raw strings for regex
- Updates to how the package builds, tests, and runs lint
- Uses PEP 517/518 metadata for build requirements/backend
- Formatting improvements, including use of isort

```text
$ git shortlog -s v20181111...v20200713
    15	Amethyst Reese
     1	Stuart Prescott
```


v20181111
---------

Version v20181111:

- Rename module to diff-match-patch to supercede existing PyPI module
- Match existing module version scheme
- Update readme, tests, etc for import names

```text
$ git shortlog -s v2018.11.06.1...v20181111
     3	Amethyst Reese
```


v2018.11.06.1
-------------

Bug fix v2018.11.06.1:

- Remove pathlib import from setup.py to fix py2 builds

```text
$ git shortlog -s v2018.11.06...v2018.11.06.1
     2	Amethyst Reese
```


v2018.11.06
-----------

Release v2018.11.06:

- Add support for Python 2.7 using conditional imports.
  Includes the upstream python2 implementation and tests,
  and selects them at import time as appropriate.

```text
$ git shortlog -s v2018.11.05...v2018.11.06
     5	Amethyst Reese
```


v2018.11.05
-----------

Initial release v2018.11.05

```text
$ git shortlog -s v2018.11.05
     3	Amethyst Reese
```

[attribution-badge]:
    https://img.shields.io/badge/generated%20by-attribution-informational
[attribution-url]: https://attribution.omnilib.dev
