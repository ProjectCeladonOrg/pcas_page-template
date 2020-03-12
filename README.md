# PCAS Page Template

This is a Django template for pages served for PCAS.  This really is not worth
looking at on its own.

### Prerequisites

* Python 3.6+
* Django
* Curiosity
* Patience

### Installing

This should be installed into your Django site home.  Just copy and paste the
files and if Django and your web server are set up properly, there is nothing
else to do.  Again, this isn't much use on its own.  Missing from this repo
are the various page templates, a database, and basic form and module data.
Those are all elsewhere.

In theory, if one were to clone all the PCAS repos and their dependencies into
the same folder and have that folder served by a web server, then the entire
site would come online.  In practice, form data is still missing.

## Contributing

Contributions can be initiated via gists and issues within GitHub.

## Versioning

We use a form of date versioning.  Versions are in the format Y.p-s, where:
Y = the full year
p = the development period (we have 5, every 73 days)
s = status (e.g. alpha1, beta2, rc1, stable)
For example:
PCAS_page-template 2020.2-alpha1 would be a valid version within this repo.

## License

This project is licensed under the AGPLv3 License - see the [LICENSE](LICENSE)
file for details.  This license has been selected intentionally and with great
thought, and is non-negotiable.
