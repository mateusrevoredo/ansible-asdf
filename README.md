# markosamuli.asdf

[![GitHub release](https://img.shields.io/github/release/markosamuli/ansible-asdf.svg)](https://github.com/markosamuli/ansible-asdf/releases)
[![License](https://img.shields.io/github/license/markosamuli/ansible-asdf.svg)](https://github.com/markosamuli/ansible-asdf/blob/master/LICENSE)

| Branch  | Status |
|---------|--------|
| master  | [![Build Status](https://travis-ci.org/markosamuli/ansible-asdf.svg?branch=master)](https://travis-ci.org/markosamuli/ansible-asdf)

Ansible role for installing [asdf] version manager for the current user.

Don't use this role on production servers as it supports installing asdf only
under user home directory.

[asdf]: https://asdf-vm.com

## Updating versions

Run the following scripts to get latest releases from GitHub and update them in
role defaults.

Update [asdf] release:

```bash
./update-release asdf
```

## License

* [MIT](LICENSE)

## Author Information

* [@markosamuli](https://github.com/markosamuli)
