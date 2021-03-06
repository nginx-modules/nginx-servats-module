########
Overview
########

*Scribe / Nginx Servats Module* an Nginx module that provides server status information.

Source Information
==================

:License:         |license|
:Build:           |travis|
:Latest Release:  |gittag|

Quality Standards
=================

- **Continuous Integration**: Utilization of `Travis CI <https://nginx-servats-module.docs.scribe.tools/ci>`_
  to provide per-commit reports on the success or failure status of our builds.
- **Tests and Coverage**: Automated testing using Ruby's rspec to query a compiled
  Nginx server and determine if it reacts and responds as intended.
- **Documentation**: Comprehensive
  `documentation and examples <https://nginx-servats-module.docs.scribe.tools/docs>`_
  compiled using the wonderful `Read the Docs <https://readthedocs.org/>`_ service.

Supported Nginx Builds
======================

While you can build this module against any version of Nginx, we only supply the
require patch files for a subset of version.

- :code:`0.8.54`—:code:`0.8.55`
- :code:`1.0.11`
- :code:`1.4.2`
- :code:`1.6.2`
- :code:`1.7.8`—:code:`1.7.10`

Documentation
=============

:General:       |docs|

All the documentation for the *Scribe / Nginx Servats Module* is provided via
compiled Sphinx files and hosted on `Read the Docs <https://readthedocs.org/>`_.
You can browser the docs via the
`website <https://nginx-servats-module.docs.scribe.tools/docs>`_ or download an
`PDF <https://readthedocs.org/projects/nginx-servats-module/downloads/pdf/latest/>`_
or
`Epub <https://readthedocs.org/projects/nginx-servats-module/downloads/epub/latest/>`_
for offline reading.

.. |license| image:: https://img.shields.io/badge/license-MIT-008ac6.svg?style=flat-square
   :target: https://nginx-servats-module.docs.scribe.tools/license
   :alt: The MIT License (MIT)
.. |travis| image:: https://img.shields.io/travis/scribenet/nginx-servats-module/master.svg?style=flat-square
   :target: https://nginx-servats-module.docs.scribe.tools/ci
   :alt: Travis Build Status
.. |gittag| image:: https://img.shields.io/github/tag/scribenet/nginx-servats-module.svg?style=flat-square
   :target: https://github.com/scribenet/nginx-servats-module/releases
   :alt: GitHub Tagged Release
.. |docs| image:: https://readthedocs.org/projects/nginx-servats-module/badge/?version=latest&style=flat-square
   :target: https://nginx-servats-module.docs.scribe.tools/docs
   :alt: Read the Docs Build Status
