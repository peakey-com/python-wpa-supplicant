# python-wpa-supplicant
---

Description goes here.

## External Dependencies

These are required dependencies that need to be installed before the project can be used:

 1. [Python3] - Application was developed and tested only with Python 3.8 in mind.
 2. [Python3-pip] - Package management for python.
 3. [pipenv] - Needed to manage/handle virtual environment (development only).

## Python/Pip Dependencies

The following lists are just for documentation purpose and are automatically installed under [Preparing for Development](#preparing-for-development).

These are needed for production and development environment:

 1. 
 
The following are only needed for development environment:
 
 1. [pytest] - Needed for running tests.
 2. [pytest-cov] - Needed for generating coverage from tests.
 3. [pylint] - Needed for doing static analysis on the source code.

## Preparing for Development

1. Ensure ``pip`` and ``pipenv`` are installed
2. Clone repository
3. ``cd`` into repository
4. Fetch development dependencies ``make install``
5. Activate virtualenv: ``pipenv shell``

## Usage

```TODO```

## Running Tests

Run tests locally using `make` if virtualenv is active:

```sh
    $ make
```

If virtualenv isn’t active then use:

```sh
    $ pipenv run make install
```

## LICENSE

```
python-wpa-supplicant, a simple way to manage your wpa_supplicant.conf.
Copyright (C) 2020  Peakey Enterprise, LLC

This file is a part of python-wpa-supplicant.

python-wpa-supplicant is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

python-wpa-supplicant is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```

[Python3]: <https://www.python.org/>
[Python3-pip]: <https://pip.pypa.io/en/stable/>
[pipenv]: <https://github.com/pypa/pipenv>
[pytest]: <https://github.com/pytest-dev/pytest/>
[pytest-cov]: <https://github.com/pytest-dev/pytest-cov/>
[pylint]: <https://github.com/PyCQA/pylint>
