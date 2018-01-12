.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
   :target: https://www.gnu.org/licenses/agpl
   :alt: License: AGPL-3

============================
DynApps Many2one Max Records
============================

* This module adds an option on many2one fields to change the initial fetch limit of 160 when
  opening the popup value list.

Installation
============

To install this module, you need to:

Install the module into odoo. No prerequites mus be installed

Configuration
=============

To configure this module, you need to:

You can change the default initial fetch limit of 160 by adding xx_max_records to the options
attribute of the field.
ex.:  <field name="tax_id" options="{'xx_max_records': 10000}"/>

Known issues / Roadmap
======================

Bug Tracker
===========

Bugs are tracked on the support page

Credits
=======

Contributors
------------

* Erwin Lemmens <erwin.lemmens@dynapps.be>

Do not contact contributors directly about support or help with technical issues.

Maintainer
----------

.. image:: static/description/icon.png
   :alt: Dynapps nv
   :target: https://www.dynapps.be

This module is maintained by the Dynapps. 

