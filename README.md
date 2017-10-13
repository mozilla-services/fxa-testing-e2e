# fxa-testing-e2e

> A set of end-to-end tests that make sure that Firefox Accounts and Firefox Sync do not regress.

[![CircleCI](https://circleci.com/gh/mozilla-services/fxa-testing-e2e.svg?style=svg)](https://circleci.com/gh/mozilla-services/fxa-testing-e2e)

.. image:: https://pyup.io/repos/github/mozilla-services/fxa-testing-e2e/shield.svg
    :target: https://pyup.io/repos/github/mozilla-services/fxa-testing-e2e/
    :alt: Updates
.. image:: https://pyup.io/repos/github/mozilla-services/fxa-testing-e2e/python-3-shield.svg
     :target: https://pyup.io/repos/github/mozilla-services/fxa-testing-e2e/
     :alt: Python 3

# Usage

Make sure you have Python's `virtualenv` installed.
Get latest Firefox Nightly and all the tools using by running:

```
./setup.sh
```

## Run tests

### Linux
```
./run.sh
```

### OS X
```
./run-osx.sh
```

# Other information

* Do not defocus the Firefox browser while it is running the tests!
