EH Forwarder Bot
================

.. image:: https://img.shields.io/badge/Python-3.x-blue.svg
   :alt: Python 3.x
   :target: https://www.python.org/
.. image:: https://img.shields.io/gitter/room/blueset/ehForwarderBot.svg
   :alt: Gitter
   :target: https://gitter.im/blueset/ehForwarderBot
.. image:: https://img.shields.io/badge/Chat-on%20Telegram-blue.svg
   :alt: Telegram support group
   :target: https://telegram.me/efbsupport
.. image:: https://readthedocs.org/projects/ehforwarderbot/badge/?version=latest
   :alt: Docs\: Stable version
   :target: https://ehforwarderbot.readthedocs.io/en/latest/
.. image:: https://readthedocs.org/projects/ehforwarderbot/badge/?version=dev
   :alt: Docs: Development version version
   :target: https://ehforwarderbot.readthedocs.io/en/dev/
.. image:: https://img.shields.io/github/tag/blueset/ehforwarderbot.svg
   :alt: tag release
   :target: https://github.com/blueset/ehForwarderBot/releases
.. image:: http://isitmaintained.com/badge/resolution/blueset/ehforwarderbot.svg
   :alt: Average time to resolve an issue
   :target: http://isitmaintained.com/project/blueset/ehforwarderbot
.. image:: http://isitmaintained.com/badge/open/blueset/ehforwarderbot.svg
   :alt: Percentage of issues still open
   :target: http://isitmaintained.com/project/blueset/ehforwarderbot
.. image:: https://img.shields.io/codacy/grade/3b2555f9134844e3b01b00700bc43eeb.svg
   :alt: Codacy grade
   :target: https://www.codacy.com/app/blueset/ehForwarderBot


.. image:: https://images.1a23.com/upload/images/SPET.png
   :alt: Banner


*Codename* **EH Forwarder Bot** (EFB) is an extensible chat tunnel framework which allows users to contact people from other chat platforms, and ultimately remotely control their accounts in other platforms.


.. toctree::
   :titlesonly:

   API/index
   getting-started
   directories

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

Media coverage
==============

* `Appinn: Send and Receive messages from WeChat on Telegram <http://www.appinn.com/eh-forwarder-bot/>`_ |br|
  *(EH Forwarder Bot – 在 Telegram 收发「微信」消息)*
* `Livc: Telegram — the true definition of IM <https://livc.io/177>`_ |br|
  *(Telegram——真正定义即时通讯)*

Glossary
========
.. glossary::

    Channel
        A class that communicates with a chat platform, also known as a plugin.

    EFB
        abbreviation for EH Forwarder Bot, this project.

    Master Channel
        A channel linked to the platform which directly interact with the user.

    Plugin
        See "channel".

    Slave Channel
        A channel linked to the platform which is controlled by the user through EFB framework.

Feel like contributing?
=======================

Anyone is welcomed to raise an issue or submit a pull request,
just remember to read through and understand the `contribution guideline <CONTRIBUTING.rst>`_ before you do so.

Related articles
================

* `Idea: Group Chat Tunneling (Sync) with EH Forwarder Bot <https://blog.1a23.com/2017/01/28/Idea-Group-Chat-Tunneling-Sync-with-EH-Forwarder-Bot/>`_
* `EFB How-to: Send and Receive Messages from WeChat on Telegram (zh-CN) <https://blog.1a23.com/2017/01/09/EFB-How-to-Send-and-Receive-Messages-from-WeChat-on-Telegram-zh-CN/>`_ (Out-dated) |br|
  *(安装并使用 EFB：在 Telegram 收发微信消息，已过时)*

License
=======

EFB framework is licensed under `GNU General Public License 3.0 <https://www.gnu.org/licenses/gpl-3.0.txt>`_.

.. code-block:: none

    EH Forwarder Bot: An extensible chat tunneling bot framework.
    Copyright (C) 2016 Eana Hufwe
    All rights reserved.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


.. |br| raw:: html

   <br />