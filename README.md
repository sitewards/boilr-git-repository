# Boilr Git Repository Template

## Project Outline

### Project Goals

Make it easier to generate git repositories in the format expected

### Similar Work

None

## Justification

Provide a consistent project format for git

## Summary

* License: MIT
* Language: en-AU

## Installation

```bash
$ boilr template download sitewards/boilr-git-repository gitrepo
```

## Updates

I update these templates regularly. If you need to fetch the newer version, try this:

```bash
$ boilr template download sitewards/boilr-git-repository gitrepo -f 
```

## Usage

Swap `foo` and `bar` for your own values.

```bash
$ mkdir foo
$ cd foo
$ git init
$ git remote set-url origin git@github.com:foo/bar.git
$ boilr template use gitrepo .
$ git add .
$ git commit -m "Initial Commit"
$ git push
```

## Thanks

- The team behind boilr (https://github.com/tmrts/boilr)

## Contributing

Contributions are always welcome! Nothing is to small, and the best place to start is to open an issue.
