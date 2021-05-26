[![Runbot Status](https://runbot.odoo-community.org/runbot/badge/flat//14.0.svg)](https://runbot.odoo-community.org/runbot/repo/github-com-oca-HouseofTours-14-)
[![Build Status](https://travis-ci.com/OCA/HouseofTours-14.svg?branch=14.0)](https://travis-ci.com/OCA/HouseofTours-14)
[![codecov](https://codecov.io/gh/OCA/HouseofTours-14/branch/14.0/graph/badge.svg)](https://codecov.io/gh/OCA/HouseofTours-14)
[![Translation Status](https://translation.odoo-community.org/widgets/HouseofTours-14-14-0/-/svg-badge.svg)](https://translation.odoo-community.org/engage/HouseofTours-14-14-0/?utm_source=widget)

<!-- /!\ do not modify above this line -->

# House Of Tours Odoo 14.0

Odoo 14 custom addons for House Of Tours

## How to use?

This is a template. It is based on [Copier](https://github.com/pykong/copier), go there
to read its docs to know how it works.

Quick answer to bootstrap a new repo:

```bash
python3 -m pip install --user pipx
export PATH="${PATH}:$(python3 -c 'import site; print(site.USER_BASE)')/bin"
# Install copier and pre-commit if missing
pipx install copier
pipx install pre-commit
pipx ensurepath
# Clone this repository
git clone git@github.com:HOUSE-OF-TOURS/HouseofTours-14.git
cd HouseofTours-14
pre-commit install
# Do your development, after
git add .
pre-commit run -a
# Fix the errors then git add . and pre-commit run -a
git commit
```

<!-- /!\ do not modify below this line -->

<!-- prettier-ignore-start -->

[//]: # (addons)

This part will be replaced when running the oca-gen-addons-table script from OCA/maintainer-tools.

[//]: # (end addons)

<!-- prettier-ignore-end -->

## Licenses

This repository is licensed under [AGPL-3.0](LICENSE).

However, each module can have a totally different license, as long as they adhere to OCA
policy. Consult each module's `__manifest__.py` file, which contains a `license` key
that explains its license.

----

OCA, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit
organization whose mission is to support the collaborative development of Odoo features
and promote its widespread use.
