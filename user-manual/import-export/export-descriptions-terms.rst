.. _export-descriptions-terms:

=============================
Export descriptions and terms
=============================

AtoM provides an export functionality that can be used to export
:term:`archival descriptions <archival description>`,
:term:`authority records <authority record>`,
:term:`archival institutions <archival institution>` and
:term:`terms <term>`. Exported descriptions and :term:`taxonomies <taxonomy>`
will be displayed in your web browser window. To save the XML export file, use
your browser's "Save page as" functionality.

.. TIP::

   We have noticed that in some cases the Safari browser will only save as HTML.
   Try using Firefox, IE, or Chrome to "Save page as" XML.

.. TIP::

   In many browsers you can also save the XML file by right-clicking the link
   under export, and choosing "Save page as."

To exit the XML export file, click on your browser's back button.

The following file types can be exported:

* EAD (hierarchical archival descriptions and associated authority records,
  archival institution descriptions and taxonomy terms)
* Dublin Core XML, MODS XML (archival descriptions and associated taxonomy terms)
* EAC (authority records)
* SKOS (hierarchical taxonomies)

.. SEEALSO::

   * :ref:`cli-bulk-export`

EAD export
==========

In the :term:`archival description` :term:`view page`, select EAD 2002 XML
under Export. This will export the current archival description plus all its
:term:`child records <child record>` and associated
:term:`authority records <authority record>`,
:term:`archival institution` descriptions and :term:`taxonomy` terms.

.. image:: images/export-ead.*
   :align: center
   :width: 80%
   :alt: Export EAD file from archival description page.

Dublin Core XML export
======================

In the :term:`archival description` :term:`view page`, select Dublin Core 1.1 XML
under Export. This will export the current archival description plus all its
:term:`child records <child record>` and associated
:term:`authority records <authority record>`,
:term:`archival institution` descriptions and :term:`taxonomy` terms.

.. image:: images/export-dublin-core.*
   :align: center
   :width: 80%
   :alt: Export Dublin Core file from archival description page.

MODS XML export
===============

If the administrator has set the default :term:`archival description` template
to MODS, this will also appear as an export option. In the
:term:`archival description` :term:`view page`, select MODS 3.3 XML under Export.
This will export the current archival description plus all its
:term:`child records <child record>` and associated
:term:`authority records <authority record>`,
:term:`archival institution` descriptions and :term:`taxonomy` terms.

.. image:: images/export-mods.*
   :align: center
   :width: 80%
   :alt: Export MODS file from archival description page.

EAC export
==========

In an :term:`authority record` :term:`view page`, select EAC under Export.
This will export the authority record currently being viewed.

.. image:: images/export-eac.*
   :align: center
   :width: 80%
   :alt: Export EAC file from authority record page.

SKOS export
===========

In AtoM 2.0, authenticated (logged-in) users can export SKOS files by clicking
on Manage term while on a term :term:`view page`.

.. image:: images/manage-term.*
   :align: center
   :width: 80%
   :alt: Finding the manage term page from View term page.

In a manage :term:`term` page, select SKOS under Export. This will
export the current term and all its narrow terms.

.. image:: images/export-eac.*
   :align: center
   :width: 80%
   :alt: Export SKOS file from manage term page.

.. TIP::

   Be aware that some browsers (e.g., Safari) may only allow you to save the
   Exported SKOS file as HTML. Firefox and Chrome provide the ability to Save
   page as XML, which enables Importing as XML into another program or into
   another version of AtoM.




:ref:`Back to top <export-descriptions-terms>`
