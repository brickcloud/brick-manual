Read the Docs: Documentation Simplified
=======================================

.. meta::
   :description lang=en: Automate building, versioning, and hosting of your technical documentation continuously on Read the Docs.

`Read the Docs`_ simplifies software documentation
by building, versioning, and hosting of your docs, automatically.
Think of it as *Continuous Documentation*.

Never out of sync |:arrows_counterclockwise:|
    Whenever you push code to your favorite version control system,
    whether that is Git, Mercurial, Bazaar, or Subversion,
    Read the Docs will automatically build your docs
    so your code and documentation are always up-to-date.
    Read more about :doc:`/integrations`.

Multiple versions |:card_index_dividers:|
    Read the Docs can host and build multiple versions of your docs
    so having a 1.0 version of your docs and a 2.0 version
    of your docs is as easy as having a separate branch or tag in your version control system.
    Read more about :doc:`/versions`.

Open Source and User Focused |:heartbeat:|
    Our code is free and `open source <https://github.com/readthedocs/>`_.
    :doc:`Our company </about>` is bootstrapped and 100% user focused.
    |org_brand| hosts documentation for over 100,000 large
    and small open source projects,
    in almost every human and computer language.
    |com_brand| supports hundreds of organizations with product and internal documentation.

.. _Read the docs: https://readthedocs.org/

You can find out more about our all the :doc:`/features` in these pages.

First steps
-----------

Are you new to software documentation
or are you looking to use your existing docs with Read the Docs?
Learn about documentation authoring tools such as Sphinx and MkDocs
to help you create fantastic documentation for your project.

* **Tutorial**: :doc:`/tutorial/index`

* **Getting started**:
  :doc:`With Sphinx </intro/getting-started-with-sphinx>` |
  :doc:`With MkDocs </intro/getting-started-with-mkdocs>` |
  :doc:`Feature Overview </features>` |
  :doc:`/choosing-a-site` | :doc:`/glossary`

* **Importing your existing documentation**:
  :doc:`Import guide </intro/import-guide>`


.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Overview
   overview/overview
   overview/requirements


Read the Docs feature overview
------------------------------

Learn more about configuring your automated documentation builds
and some of the core features of Read the Docs.

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Using Brick
   
   user-management/usermanagement
   container-deployment/apps
   container-deployment/quickstart
   container-deployment/yaml


How-to Guides
-------------

These guides will help walk you through specific use cases
related to Read the Docs itself, documentation tools like Sphinx and MkDocs
and how to write successful documentation.


.. toctree::
 :maxdepth: 2
 :hidden:
 :caption: How-to Guides

 /guides/authors
 /guides/administrators
 /guides/developers

Advanced features of Read the Docs
----------------------------------

Read the Docs offers many advanced features and options.
Learn more about these integrations and how you can get the most
out of your documentation and Read the Docs.

* **Advanced project configuration**:
  :doc:`subprojects` |
  :doc:`Single version docs <single_version>` |
  :doc:`feature-flags`

* **Multi-language documentation**:
  :doc:`Translations and localization <localization>`

* **Redirects**:
  :doc:`Automatic redirects <automatic-redirects>`

* **Versions**
  :doc:`Automation rules <automation-rules>`

* **Topic specific guides**:
  :doc:`How-to guides <guides/index>`

* **Extending Read the Docs**:
  :doc:`REST API <api/index>`

.. toctree::
   :maxdepth: 2
   :hidden:
   :glob:
   :caption: Advanced features

   subprojects
   single_version
   feature-flags

   localization

   user-defined-redirects
   automatic-redirects

   automation-rules


   api/index

Read the Docs for Business
--------------------------

Read the Docs has a commercial offering with improved support and additional features.

* **Read the Docs for Business**:
  :doc:`Organizations <commercial/organizations>` |
  :doc:`Single Sign On <commercial/single-sign-on>` |
  :doc:`Project Privacy Level <commercial/privacy-level>` |
  :doc:`Sharing externally <commercial/sharing>`


.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Read the Docs for Business
   :glob:

   commercial/*

The Read the Docs project and organization
------------------------------------------

Learn about Read the Docs, the project and the company,
and find out how you can get involved and contribute to the development and success
of Read the Docs and the larger software documentation ecosystem.

* **Policies & Process**:
  :doc:`security` |
  :doc:`DMCA takedown policy <dmca/index>` |
  :doc:`Policy for abandoned projects <abandoned-projects>` |
  :doc:`Release notes & changelog <changelog>`

* **The people and philosophy behind Read the Docs**:
  :doc:`About Us </about>` |
  :doc:`Team <team>` |
  :doc:`Open source philosophy <open-source-philosophy>` |
  :doc:`Our story <story>`

* **Financial and material support**:
  :doc:`advertising/index` |
  :doc:`Sponsors <sponsors>`

* **Legal documents**:
  :doc:`Terms of service <terms-of-service>` |
  :doc:`Privacy policy <privacy-policy>` |
  :doc:`Data processing agreement <legal/dpa/index>`

* **Getting involved with Read the Docs**:
  :doc:`Developer Documentation <rtd-dev:index>` |
  :doc:`/gsoc`


.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: About Read the Docs

   security
   dmca/index
   abandoned-projects
   changelog

   about
   team
   open-source-philosophy
   story

   advertising/index
   sponsors

   legal/index

   Developer Documentation <https://dev.readthedocs.io>
   gsoc






Welcome to Brick's Documentation!
===================================

**Brick** 은 Google Kubernetes 기반의 컨테이너 관리 소프트웨어입니다. 
컨테이너 배포 및 운영 관련하여 다양한 기능들을 제공하여, 기업들이 온프레미스 환경의 Kubernetes 클러스터를 통해
컨테이너 기반의 애플리케이션을 쉽고 편리하게 운영할 수 있도록 해줍니다.
애플리케이션을 Kubernetes 기반에서 컨테이너로 빠르게 배포하고 관리할 수 있습니다.

Check out the documentation:doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   We are working on adding new features to Brick.
