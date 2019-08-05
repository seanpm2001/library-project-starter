# {REPO}

{PROJECT_DESCRIPTION}

## Status

[![CircleCI](https://circleci.com/gh/{REPO_OWNER}/{REPO}.svg?style=svg)](https://circleci.com/gh/{REPO_OWNER}/{REPO})

{PROJECT_STATUS}

## Installation

* Install [pony-stable](https://github.com/ponylang/pony-stable)
* Update your `bundle.json`

```json
{
  "type": "github",
  "repo": "{REPO_OWNER}/{REPO}"
}
```

* `stable fetch` to fetch your dependencies
* `use "{PACKAGE}"` to include this package
* `stable env ponyc` to compile your application
