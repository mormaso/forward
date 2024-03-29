=========
Changelog
=========

All notable changes to this project will be documented in this file.

The format is based on `Keep a Changelog`_, adapted for reStructuredText syntax.
This project adheres to `Semantic Versioning`_-flavored `PEP 440`_.

.. _Keep a Changelog: https://keepachangelog.com/en/1.0.0/
.. _PEP 440: https://www.python.org/dev/peps/pep-0440/
.. _Semantic Versioning: https://semver.org/spec/v2.0.0.html

Unreleased
==========

Added
-----
- Add ``get_chat_picture()`` method to allow slave channels to provide profile pictures for members of chats. (`#310`_ by @ojhdt)

Changed
-------

Removed
-------

Fixed
-----

Known issue
-----------

2.1.1_ - 2021-05-22
===================

Changed
-------
- Changed the critical log colors for better contrast

Fixed
-----
- :kbd:`^c` not able to terminate initialization process due to the handler
  registered.

2.1.0_ - 2020-11-23
===================

Added
-----
- 5 consequent SIGTERM or SIGINT will trigger a force quit.
- Allow user to trace hanging threads to debug *graceful exit*-related issues.

Fixed
-----
- Blocking main thread to keep thread pools running throughout the session (`#225`_)

2.0.0_ - 2020-01-31
===================
First release.

.. _2.0.0: https://efb.1a23.studio/releases/tag/v2.0.0
.. _2.1.0: https://efb.1a23.studio/compare/v2.0.0...v2.1.0
.. _2.1.1: https://efb.1a23.studio/compare/v2.1.0...v2.1.1
.. _#225: https://efb.1a23.studio/issues/225
.. _#310: https://efb.1a23.studio/pull/310
