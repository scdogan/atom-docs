.. _settings:

========
Settings
========

This section describes how to customize your AtoM application to the
specific requirements of your own institution or :term:`network`.

Below, you will find information on the following :term:`information areas
<information area>`:

* :ref:`Global settings <global-settings>`
* :ref:`Site information <site-information>`
* :ref:`Default page elements <default-page-elements>`
* :ref:`Default templates <default-templates>`
* :ref:`User interface labels <user-interface-labels>`
* :ref:`Add/Remove languages <add-remove-languages>`
* :ref:`OAI repository <oai-repository>`
* :ref:`Job scheduling <job-scheduling>`
* :ref:`Security panel <security-panel>`

.. _global-settings:

Global settings
===============

.. |gears| image:: images/gears.png
   :height: 18
   :width: 18

Global settings allow :term:`administrators <administrator>` to control certain
aspects of how AtoM appears and behaves.

To access the "Settings" menu in AtoM, click on the |gears| :ref:`Admin
menu <main-menu-admin>` in the :term:`main menu` located in the
:term:`header bar` and select "Settings" from the :term:`drop-down menu`. You
will be redirected to the "Site Settings", where a number of :term:`information
areas <information area>`, including the "Global" settings, should be opened.
If closed, simply click on the "Global" blue menu to open the area and view the
:term:`fields <field>`.

.. image:: images/global-settings.*
   :align: center
   :width: 70%
   :alt: An image of the Global settings in AtoM

This section will describe each :term:`field` in the "Global"
:term:`information area`:

* :ref:`Application version <application-version>`
* :ref:`Check for updates <check-updates>`
* :ref:`Maximum image width <max-image-width>`
* :ref:`Results per page <results-page>`
* :ref:`Accession mask <accession-mask>`
* :ref:`Accession counter <accession-counter>`
* :ref:`Reference code separator <reference-code-separator>`
* :ref:`Inherit reference code (Information object) <inherit-reference-code>`
* :ref:`Sort treeview (information object) <sort-treeview>`
* :ref:`Sort browser (users) <sort-browser-users>`
* :ref:`Sort browser (anonymous) <sort-browser-anonymous>`
* :ref:`Multiple repositories <multiple-repositories>`
* :ref:`Default archival institution upload limit <default-institution-upload>`
* :ref:`Total space available for uploads <total-upload-space>`
* :ref:`Upload multi-page files as multiple descriptions <upload-multi-files>`
* :ref:`Show tooltips <tooltips>`
* :ref:`Default publication status <default-publication-status>`
* :ref:`SWORD deposit directory <sword-directory>`

Hovering over each :term:`field` will also provide additional information on
that field - it will appear in a white "information box" below your cursor.

When making changes to the global settings in AtoM, don't forget to click the
"Save" button in the :term:`button block`, located at the bottom of the "Global"
settings :term:`information area`.

.. _application-version:

Application version
-------------------

This :term:`field` shows the current version of the software. The value is pre-
set, ships with the application, and cannot be edited. The version number is
automatically updated when AtoM is upgraded to a newer release.

For more information on installing AtoM and searching for different versions,
see:

* Installing AtoM with:

  * :ref:`Linus <installation-linux>`
  * :ref:`Windows <installation-windows>`
  * :ref:`Mac OS X <installation-macosx>`

* :ref:`Search for updates <search-updates>`

.. _check-updates:

Check for updates
-----------------

If yes is selected, an :term:`administrator` will automatically receive a
notification if a newer version of the AtoM software has been released and can
be installed.

For more information on updates, see:

* :ref:`Search for updates <search-updates>`

.. _max-image-width:

Maximum image width (pixels)
----------------------------

One of AtoM's design assumptions is that the display dimensions of files
users upload typically will be too large to fit into the :term:`view page` for
an :term:`archival description`. Therefore, when you upload a file, AtoM creates
a :term:`reference display copy` for displaying in the view page.

AtoM ships with a default setting specifying the maximum width of the
:term:`reference display copy` at **480 pixels**. This is the optimized width
given AtoM's :term:`field` width. :term:`Administrators <administrator>`,
however, can increase or decrease the maximum reference image
width to suit the requirements of their institution or network.

.. seealso::

   * :ref:`Styling static pages <styling-static-page>`
   * :ref:`Themes & Theming <themes-theming>`

.. _results-page:

Results per page
----------------

By default, AtoM lists objects in list pages and search results **ten at a
time**, with a pager at the bottom of the page to allow users to navigate
through long lists of objects. :term:`Administrators <administrator>` can
increase or decrease this default number.

For more information on navigating in AtoM, see :ref:`Searching in AtoM
<search-atom>` and :ref:`Navigating in AtoM <navigate>`.

.. _accession-mask:

Accession mask
--------------

By default, AtoM creates the :term:`accession record` identifier as a unique
number compiled from [YEAR MONTH DAY Incremental#].

For more information on accession records, see :ref:`accession-records`.

.. _accession-counter:

Accession counter
-----------------

AtoM provides you with the number of :term:`accessions <accession record>`
created. If you delete an accession, it will still be included in the Accession
counter total value.

.. _reference-code-separator:

Reference code separator
------------------------

The reference code separator is the character separating hierarchal elements in
a reference code. By default, the reference code separator appears as a dash "-"
in AtoM.

.. _inherit-reference-code:

Inherit reference code (information object)
-------------------------------------------

When this is set to "yes", the reference code string will be built using the
archival description identifier plus the identifier of all its ancestors
(:term:`parent records <parent record>`). For more information about how the
reference code works, see :ref:`search-archival-descriptions`.

.. _sort-treeview:

Sort treeview (information object)
----------------------------------

This setting determines how lower-level :term:`descriptions <archival
description>` are sorted in an :term:`archival description's <archival
description>` :term:`context menu`.

Selecting "manual" means the descriptions will appear in the order in which they
were entered into AtoM.
Selecting "title" sorts the descriptions by title.
Selecting "identifier - title" sorts the descriptions by identifier, then by
title.

For more information, see :ref:`treeview-search`.

.. _sort-browser-users:

Sort browser (users)
--------------------

:term:`Administrators <administrator>` can configure default sort order for the
browse display as either "alphabetic" or "last updated" for logged-in users.

.. seealso::

   * :ref:`Browsing in AtoM <browse>`
   * :ref:`user-roles`

.. _sort-browser-anonymous:

Sort browser (anonymous)
------------------------

:term:`Administrators <administrator>` can configure default sort order for the
browse display as either, "alphabetic" or "last updated" for public users
(e.g., not logged-in).

.. seealso::

   * :ref:`Browsing in AtoM <browse>`
   * :ref:`user-roles`

.. _multiple-repositories:

Multiple repositories
---------------------

Select "yes" if your AtoM application is acting as a union list or portal for
:term:`descriptions <archival description>` of materials held at more than one
:term:`archival institution` or :term:`repository`. The repository will appear
as a column on the "Browse archival descriptions" page. The repository will
appear as a link in the :term:`context menu`.

Select "no" if your AtoM application is being used only by a single institution.
By selecting "no", the repository name will be excluded from certain displays
because it will be too repetitive and the :term:`creator` rather than the
repository will now appear as a column on the list :term:`archival description`
page.

.. seealso::

   * :ref:`Browsing in AtoM <browse>`
   * :ref:`archival-descriptions`
   * :ref:`archival-institutions`

.. _default-institution-upload:

Default archival institution upload limit (GB)
----------------------------------------------

"1" is the value for unlimited upload. This setting can be modified by an
authenticated (i.e. logged-in) :term:`administrator`.

A value of "0" (zero) disables file upload. A value of "-1" allows unlimited
uploads.

For more information, see :ref:`upload-digital-objects`.

.. _total-upload-space:

Total space available for uploads
---------------------------------

contentcontentcontent

.. _upload-multi-files:

Upload multi-page files as multiple descriptions
------------------------------------------------

Select "yes" if you would like each page of a multi-page file to be attached to
a separate child-level description. For example, a PDF file with 10 pages
uploaded to a description would result in 10 individual descriptions, one for
each page in the file.

Select, "no" if you would like one multi-page file to be attached to a single
description.

.. seealso::

   * :ref:`archival-descriptions`

.. _tooltips:

Show tooltips
-------------

:term:`Tooltips` are online text designed to assist users to enter data in
:term:`edit pages <edit page>`.

:term:`Administrators <administrator>` can select "yes" to to have tooltips
appear in :term:`edit pages <edit page>` as the user enters data. Selecting "no"
will disable tooltips.

.. _default-publication-status:

Default publication status
--------------------------

This setting determines whether new :term:`archival descriptions <archival
description>` will automatically appear as :term:`draft records <draft record>`
or :term:`published records <published record>`. Note that this setting also
affects imported descriptions. For more information, see
:ref:`archival-descriptions`.

.. _sword-directory:

SWORD deposit directory
-----------------------

In 1.3 release, the SWORD deposit directory is being used to support packages
deposited by Archivematica into AtoM. (In future releases we will use this
protocol to interact with other systems.) Developers interested learning more
about SWORD can click `here
<https://www.qubit-toolkit.org/wiki/SWORD#Packaging_formats_supported>`__.

:ref:`Back to top <settings>`


.. _site-information:

Site information
================

In this section, :term:`administrators <administrator>` can change the site
title and site description. To save any modifications, be sure to click "Save"
button located below the "Site Description" field.

.. image:: images/site-information.*
   :align: center
   :width: 70%
   :alt: An image of the Site information menu in AtoM

:ref:`Back to top <settings>`

.. _default-page-elements:

Default page elements
=====================

This section allows :term:`administrators <administrator>` to enable or disable
certain page elements. Unless they have been overridden by a specific theme,
these settings will be used site-wide.

.. image:: images/default-page-elements.*
   :align: center
   :width: 70%
   :alt: An image of the Default page elements menu in AtoM

Simply check or uncheck boxes to modify the current settings of your site.

For more information on page elements, see `Themes & Theming <themes-theming>`.

:ref:`Back to top <settings>`

.. _default-templates:

Default templates
=================

AtoM ships with default page layouts ("templates") for viewing and editing
:term:`archival descriptions <archival description>`, :term:`authority records
<authority record>`, and :term:`archival institutions <archival
institution>`. For more information on the standards on which these
templates are based, see :ref:`descriptive-standards`.

.. image:: images/default-template.*
   :align: center
   :width: 70%
   :alt: An image of the Default template menu in AtoM

The "Name" column shows the types of :term:`entities <entity>` that are
described in AtoM: "Archival descriptions", "Authority records" and "Repository
records". :term:`Drop-down menus <drop-down menu>` of descriptive standards for
each are provided under the "Value" column. These drop-down menus
term:`Administrators <administrator>` may select one for each entity.

Once changes have been saved, records on the site will be able to be viewed in
the templates that have been selected.

:ref:`Back to top <settings>`

.. _user-interface-labels:

User interface labels
=====================

Users of AtoM interact with six main :term:`entities <entity>`: :term:`accession
records <authority record>`, :term:`archival descriptions <archival
description>`, :term:`authority records <authority record>`, :term:`archival
institutions <archival institution>`, :term:`functions <function>` and
:term:`terms <term>`.

.. seealso::

   * :ref:`entity-types`
   * :ref:`recurring-facet-filters`

AtoM is flexible enough to support descriptions of other types of cultural
materials in addition to library holdings (such as archival, museum, and art
gallery materials). The code, therefore, uses generic terms for entities.
:term:`Administrators <administrator>` can specify how they want these
:term:`terms <term>` to appear in the :term:`user interface` labels. The default
labels that ship with AtoM represent an archives-specific "theming" of the
labels.

Changes made here:

.. image:: images/user-interface-label.*
   :align: center
   :width: 70%
   :alt: An image of the User interface labels menu in AtoM

will alter the titles that appear here:

.. image:: images/facet-filters.*
   :align: center
   :width: 70%
   :alt: Facet filters available on an archival description browse page

The "Name" column shows the generic entity name and the "Value" column
shows AtoM's default user interface labels. The following is a list of the
generic terms and their AtoM user interface labels. Click on each label below to
see glossary definitions and descriptions of how the terms are used in AtoM.

* informationobject: :term:`archival description`
* actor: :term:`Authority record`
* creator: :term:`Creator`
* repository: :term:`Archival institution`
* function: :term:`Function`
* term: :term:`Term`
* subject: :term:`Subject`
* collection: :term:`Fonds`
* holdings: :term:`Holdings`
* place: :term:`Place`
* name: :term:`Name`
* digitalobject: :term:`Digital object`
* physicalobject: :term:`Physical storage`
* mediatype: :term:`Media type`
* materialtype: Material type (general material designations used in the
  :ref:`Canadian Rules for Archival Description <rad-template>`).
* facetstitle: :term:`facets title`

:term:`User interface <user interface>` labels can be changed by
:term:`administrators <administrator>` by entering a new label(s) into the
:term:`field(s) <field>` under the "Value" column. Changes will only be
saved once the "Save" button is clicked.

.. NOTE::

   Changing the user interface labels will *not* automatically change the
   corresponding labels in the navigation menus. To change these menus, go to
   **Admin > Menus**. See the :ref:`Manage menus <manage-menus>` page for more
   information.

:ref:`Back to top <settings>`

.. _add-remove-languages:

Add/Remove languages
====================

As of the 2.0.0 release of AtoM, Artefactual has begun using Transifex to
manage the translations of its English content in various other languages.
Transifex is a version-control system and repository that allows Artefactual to
manage translation quality without havint to worry about spreadsheets, emails
and FTP servers. It also allows for extended collaboration with AtoM users and
contributors; all translations of the original AtoM website are completed by
volunteers outside the organization. For more information on Transifex, visit
their `website <https://www.transifex.com/>`__. The latest update of translated
strings in AtoM is available
`here <https://www.transifex.com/projects/p/atom/r/2/>`__

.. image:: images/add-remove-languages.*
   :align: center
   :width: 70%
   :alt: An image of the add/remove languages menu in AtoM

The language menu will display the languages that are currently available in
your AtoM application; the current (active) language is underlined.

.. |delete| image:: images/xdelete.png
   :height: 18
   :width: 18

.. |globe| image:: images/globe.png
   :height: 18
   :width: 18

**To add a language:**

#. Select a language from the :term:`drop-down menu` located under "Language
   code".
#. Click the "Add" button.
#. AtoM adds the language and refreshes the page; the added language will now
   appear in the "Add/remove languageA section in "Settings", as well as in the
   :term:`drop-down menu` of the |globe| :term:`language navigation menu
   <language menu>` located at the top right corner of the :term:`header bar`.

.. NOTE::

   It is possible that some languages will be supported in AtoM (i.e. they will
   appear when added to the "Add/remove language" section in "Settings"), but
   not all of the English content will have been translated in its entirety
   (i.e. if the language is selected from the **Language menu** in the
   :term:`header bar`, content that has not yet been translated will remain in
   English).

To continue adding languages, repeat these steps as required.

.. NOTE::

   If a user selects a language that is not currently supported (i.e., where
   the content has not yet been translated through Transifex), AtoM will
   refresh the settings screen without implementing any changes.

**To remove a language:**

#. Click the delete |delete| located in the third (blank) column next to the
   language.
#. AtoM will delete the language and refresh the page; the deleted language will
   no longer appear in the "Add/remove language" section in "Settings", nor in
   the :term:`drop-down menu` of the |globe| :term:`language navigation menu
   <language menu>` located at the top right corner of the :term:`header bar`.

To continue removing languages, repeat these steps as required.

.. seealso:

   * :ref:`choose-language`
   * :ref:`default-language`
   * :ref:`language-menu`

:ref:`Back to top <settings>`


.. _oai-repository:

OAI repository
==============

OAI (or Open Archives Initiative) is a protocol for metadata harvesting that
allows for the automatic data harvesting and crawling within other systems that
support OAI harvesters. For more information on OAI, visit the `OAI-PMH wiki
<https://www.qubit-toolkit.org/wiki/OAI-PMH>`__.

.. image:: images/oai-repository.*
   :align: center
   :width: 70%
   :alt: An image of the OAI repository menu in AtoM

Below, you will find information on the following :term:`information areas
<information area>`:

* :ref:`Enable OAI <enable-oai>`
* :ref:`OAI repository code <oai-repository-code>`
* :ref:`OAI repository identifier <oai-repository-identifier>`
* :ref:`Sample OAI identifier <sample-oai-identifier>`
* :ref:`Resumption token limit <resumption-token-limit>`

.. WARNING::

   This feature was developped for earlier versions of AtoM and has not been
   tested in AtoM 2.x. We hope to improve OAI features in future version
   releases of AtoM.

.. _enable-oai:

Enable OAI
----------

Select "yes" if you want the system to act as an OAI repository and respond to
OAI harvesting requests.

.. _oai-repository-code:

OAI repository code
-------------------

An alpha-numeric code can be added in the value field to uniquely identify this
particular OAI repository within its network domain to create a unqiue, OAI
compliant identifier.

.. _oai-repository-identifier:

OAI repository identifier
-------------------------

This is an auto-generated setting that produces an OAI compliant repository
identifier, which includes OAI repository code value if it is set.

.. _sample-oai-identifier:

Sample OAI identifier
---------------------

This is an example of the auto-generated, OAI compliant identifier which is
created for each item in this particular OAI repository.

.. _resumption-token-limit:

Resumption token limit
----------------------

This relates to the number of :term:`entities <entity>` to include in a single
OAI response list before inserting a resumption token.

:ref:`Back to top <settings>`


.. _job-scheduling:

Job scheduling
==============

In Release 1.3, job scheduling was introduced, using `Gearman
<http://gearman.org/>`__, to make AtoM capable of running applications in the
background. At present, the only process that makes use of this feature is
SWORD.

.. image:: images/job-scheduling.*
   :align: center
   :width: 70%
   :alt: An image of the Job scheduling menu in AtoM

In future releases, we plan to extend the capabilities of job scheduling to
allow :term:`administrators <administrator>` to upload digital objects (e.g.,
large video files) and close their browser while continuing to run the upload
process.

:ref:`Back to top <settings>`

.. _security-panel:

Security panel
==============

The "Security panel" was a new Security feature provided in the 1.3 Release of
AtoM.

The application ships with default values of "no", but an :term:`administrator`
can select "yes" and increase security.

.. image:: images/security-panel.*
   :align: center
   :width: 70%
   :alt: An image of the add/remove languages menu in AtoM

Below is a an brief explanation of each :term:`information area`:

* "Limit adminsitrator functionality to one or more IP addresses, separated by
  semicolons": limits incoming requests for all administrator functionality to
  an IP address or an IP range. Two examples:

  * 192.168.0.1
  * 192.168.0.1;192.168.0.255

* "Require SSL for all administrator functionality": see `TLS
  <https://www.qubit-toolkit.org/wiki/TLS>`__ for more details
* "Require strong passwords": enhance login validation to force use of strong
  passwords. At least 8 characters long, containing characters from 3 of the
  following classes:

  #. Upper case letters
  #. Lower case letters
  #. Numbers
  #. Special characters

:ref:`Back to top <settings>`