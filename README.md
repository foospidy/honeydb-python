# honeydb-python

[![Latest Version](https://img.shields.io/pypi/v/honeydb.svg)](https://pypi.python.org/pypi/honeydb/)
[![Build Status](https://travis-ci.org/foospidy/honeydb-python.svg?branch=master)](https://travis-ci.org/foospidy/honeydb-python)

HoneyDB Python Module

### Install

`pip install honeydb`

### CLI Usage

```
$ export HONEYDB_API_ID=<your api id>
$ export HONEYDB_API_KEY=<your api key>
$ honeydb --bad-hosts
```

Display help message for more CLI options:

`honeydb --help`

### Module Usage

```
from honeydb import api
honeydb = api.Client('api_id', 'api_key')
print(honeydb.bad_hosts())
```
