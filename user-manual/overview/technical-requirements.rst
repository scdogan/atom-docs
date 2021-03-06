.. _technical-requirements:

=======================
Technical Requirements
=======================

Server-side requirements (for installation, hosting, etc.)
==========================================================

Details for the hardware and server environment, and the software
dependencies (both required and recommended) have been documented in our
:ref:`Administator Manual <admin-manual-home>`. For further details, see:
:ref:`installation-requirements`.


Client-side requirements (for end users)
========================================

AtoM has been designed with minimal assumptions about the technology
available to users and contributors. All that is required is access to the
internet and a web browser (any web browser will do, though use of a modern
web browser is strongly encouraged). AtoM does, however, rely on "client-side"
JavaScript to achieve certain effects when displaying content:

* on :term:`edit pages <edit page>`, :term:`fields <field>` are grouped into
  :term:`information areas <information area>` that are "collapsible" (i.e.,
  fields can be displayed or hidden)
* Some :term:`drop-down menus <drop-down menu>` are collapsible (i.e. options
  in the list can be expanded to display more options or collapsed to hide them)

Older browsers that do not support JavaScript will not be able to view these
effects. They are still able to access AtoM unimpaired; it just won't look as
nice. It is recommended, therefore, that users employ modern web browsers
that support JavaScript (such as `Firefox
<http://www.mozilla.org/en-US/firefox/fx/#desktop>`_, `Chrome
<https://www.google.com/intl/en_uk/chrome/browser/>`_, `Opera
<http://www.opera.com/browser/>`_, or `Safari
<http://www.apple.com/safari/>`_.)


Internet Explorer 8 and AtoM 2.0
================================

With the release of 2.0, AtoM will no longer support Internet
Explorer (IE) 8 or earlier versions. If possible, please upgrade your browser
to IE9 or higher, or use a supported browser such as `Firefox
<http://www.mozilla.org/en-US/firefox/fx/#desktop>`_,
`Chrome <https://www.google.com/intl/en_uk/chrome/browser/>`_,
`Opera <http://www.opera.com/browser/>`_, or `Safari
<http://www.apple.com/safari/>`_.

Alternately, if you are unable to update your browser, we recommend
installing the `Google Chrome Frame
<https://developers.google.com/chrome/chrome-frame/>`_ for Internet Explorer:

        *"Google Chrome Frame is an open source browser plug-in. Users who have
        the plug-in installed have access to Google Chrome's open web
        technologies and speedy JavaScript engine when they open pages in the
        browser.*

        *Google Chrome Frame seamlessly enhances your browsing experience in
        Internet Explorer. It displays Google Chrome Frame enabled sites using
        Google Chrome’s rendering technology, giving you access to the latest
        HTML5 features as well as Google Chrome’s performance and security
        features without in any way interrupting your usual browser usage."*

More information on Google's Chrome Frame can be found `here
<https://en.wikipedia.org/wiki/Google_Chrome_Frame>`_

.. note:: Google has announced that it will no longer be providing support
   for the Chrome Frame after January 2014

To Install Chrome Frame:
------------------------

#. Open Internet Explorer (version 7, 8, or 9)
#. Navigate to: http://www.google.com/chromeframe
#. Follow the download and installation instructions

* You will first have to agree to Google's Terms and Conditions of Use:

.. image:: images/chromeframe-1-terms.*

4. The installation should only take a moment, and you will not see any
   noticeable change in the browser

.. image:: images/chromeframe-2-install.*

5. Remember, if you need to manage or uninstall this add-on, you can do so in
   Internet Explorer by going to Tools > Manage Add-ons and selecting the
   Chrome Frame add-on from the list.
