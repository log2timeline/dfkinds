# Installation instructions

## pip

**Note that using pip outside virtualenv is not recommended since it ignores
your systems package manager. If you aren't comfortable debugging package
installation issues use virtualenv.**

Create and activate a virtualenv:

```bash
virtualenv dfkinds_venv
cd dfkinds_venv
source ./bin/activate
```

Upgrade pip and install dfKinds dependencies:

```bash
pip install --upgrade pip
pip install dfkinds
```

To deactivate the virtualenv run:

```bash
deactivate
```
