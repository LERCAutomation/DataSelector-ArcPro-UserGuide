*******
Preface
*******

The most up to date version of this documentation can be found in **HTML** and **PDF** form on `ReadTheDocs <https://readthedocs.org/projects/dataselector-arcpro-userguide/>`_.

.. index::
	single: Recommended user knowledge

Recommended User Knowledge
==========================

Users
-----

This user guide assumes that users of the ArcGIS Pro version of the Data Selector tool have:

* General IT experience including use of Microsoft Windows.
* Experience in the use of the GIS application ArcGIS Pro supported by this version of the tool.
* An understanding of the data held in the Recorder6 database that has been configured for use by the Data Selector tool.

Administrators
--------------
It is recommended that a person within each organisation is designated as the tool and database administrator. This person should:

* Have an understanding and experience of IT systems management.
* Understand relational database structures.
* Have an good understanding of how to write Structure Query Language (SQL).
* Become familiar with how the Data Selector tool has been configured within the organisation.
* Have a good understanding of XML.

.. raw:: latex

   \newpage

.. index::
	single: Reading guide

Reading Guide
=============

This Preface explains a little about the Data Selector tool, the community of people who develop and use it, and the licensing conditions for using and distributing it. It also explains how to read this user guide.

:doc:`../introduction/introduction` \ explains why the Data Selector tool is needed, what it does and where it comes from.

:doc:`Extending Recorder6 <../recorder/recorder>` \ is a brief outline of how and how Recorder6 can be extended to enable the Data Selector tool to get the most out of your biological data.

:doc:`Setting up the tool <../setup/setup>` \ describes how to install and set up the Data Selector tool.

:doc:`Running the tool <../execute/execute>` \ describes how to run the Data Selector tool.

:doc:`FAQs <../faq/faq>` \ has a list of commonly asked questions and their answers.

:doc:`../appendix/appendix` \ contains an example of an XML configuration file for ArcGIS Pro and contains a copy of the GNU Free Documentation License v1.3 covering this guide.


.. index::
	single: Licensing

Licensing
=========

The code for the Data Selector tool is 'open source' and is released under the `GNU General Public License (GPL) v3 <http://www.gnu.org/licenses/gpl.html>`_. Users are free to install it on as many computers as they like, and to redistribute it according to the GPLv3 license.

This guide is released under the `GNU Free Documentation License (FDL) v1.3 <http://www.gnu.org/licenses/fdl.html>`_. Permission is granted to copy, distribute and/or modify this document under the terms of the license.

Please remember, however, that the tool cost a lot of money to develop and still requires further development and ongoing support. Hence any contributions towards costs would be gratefully received. Enquiries can be made via email to `Andy Foy <mailto:andy@andyfoyconsulting.co.uk>`_.


.. index::
	single: Useful links

Useful links
============

Related community links:

* Administrators (`Releases <https://github.com/LERCAutomation/DataSelector-ArcPro/releases/>`_) - Release notes and installers for ArcGIS Pro.
* Developers (`Source code <https://github.com/LERCAutomation/DataSelector-ArcPro>`_) - Source code for the ArcGIS Pro version of the Data Selector Tool.
* Issues (`Issues <https://github.com/LERCAutomation/DataSelector-ArcPro/issues>`_) - Details of known issues and existing change requests.


.. raw:: latex

	\newpage

.. index::
	single: Acknowledgements

Acknowledgements
================

The DataSelector tool was developed with funding from:

* Greenspace Information for Greater London CIC
* Thames Valley Environmental Records Centre
* Sussex Biodiversity Records Centre
* Surrey Biodiversity Information Centre

And with additional funding from:
* Dorset Environmental Records Centre
* Isle of Wight Local Records Centre

Many thanks are due to all the LERCs and their staff who have, and continue to, fund and contribute towards the DataSelector tool.


.. raw:: latex

	\newpage

.. index::
	single: Conventions used in this user guide

Conventions used in this user guide
===================================

The following typographical conventions are used in this manual:

:kbd:`Ctrl-A`
	Indicates a key, or combination of keys, to press.

**Commit**
	Indicates a label, button or anything that appears in user interfaces.

**Tools... --> About**
	Indicates a menu choice, or a combination of menu choices, tab selections or GUI buttons.

:file:`D:\\DataTools\\DataSelector\\Config`
	Indicates a filename or directory name.

.. tip::
	Tips can help save time or provide shortcuts.

.. seealso::
	References and/or links to other sections of this guide.

.. note::
	Notes explain things in more detail or highlight important points.

.. caution::
	Warnings where users should pay attention.
