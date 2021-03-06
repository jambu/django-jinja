Changelog
=========

Version 0.23
------------

- Add settings JINJA2_FILTERS_REPLACE_FROM_DJANGO
- Add settings JINJA2_MUTE_URLRESOLVE_EXCEPTIONS
- Improvements on cache tag.
- Other bugfixes.


Version 0.22
------------

- Change template order selection.
- New contrib: subdomains
- New contrib: dajax-ice
- Documentation fixes.
- Minor improvements.

Version 0.21
------------

- Remove obsolete __version__ variable from __init__.py file.
- Add bytecode cache with django cache framework support.

Version 0.20
------------

- Introduce backward incompatible change: all contrib apps
  are renamed (prepened _ on each module name) for avoid
  name conflicts with the original package.

Version 0.19
------------

- Bugfixes related to autoescape.

Version 0.18
------------

- Test singnal when stream template method is used.

Version 0.17
------------

- Add 4xx/500 django special views.

Version 0.16
------------

- Remove distribute dependency.


Version 0.15
------------

- Put autoescape ON by default.
- Add easy_thumbnails contrib app
- Add django humanize contrib app

Version 0.14
------------

- Add jinja2 extensions loading by default

Version 0.13
------------

- New intercept method by regex is added.
- Documentation improvements.

Version 0.12
------------

- Minor fixes

Version 0.11
------------

- Add full django-pipeline support (contrib app)
