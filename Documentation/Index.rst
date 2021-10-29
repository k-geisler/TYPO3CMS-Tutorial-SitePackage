.. include:: Includes.txt


.. _start:

=====================
Site package tutorial
=====================

This tutorial describes the steps required to turn a basic design template
(HTML, CSS, JavaScript files, etc.) into a fully working, mobile-responsive
website powered by TYPO3. By creating a site package extension, all relevant
files are stored at a central point and
changes can easily be tracked in version control.

Despite the fact that TYPO3 supports several methods of implementing websites,
this approach is a very flexible and professional way. Programming
knowledge is useful but not required.


.. container:: row m-0 p-0

   .. container:: col-md-6 pl-0 pr-3 py-3 m-0

      .. container:: card px-0 h-100

         .. rst-class:: card-header h3

            .. rubric:: :ref:`Preface <preface>`

         .. container:: card-body

            You can learn here about the history of this tutorial and learn
            how to give feedback.

   .. container:: col-md-6 pl-0 pr-3 py-3 m-0

      .. container:: card px-0 h-100

         .. rst-class:: card-header h3

            .. rubric:: :ref:`Introduction <introduction>`

         .. container:: card-body

            An introduction in the concepts behind using a site package
            extension

   .. container:: col-md-6 pl-0 pr-3 py-3 m-0

      .. container:: card px-0 h-100

         .. rst-class:: card-header h3

            .. rubric:: :ref:`Design template <design-template>`

         .. container:: card-body

            Introduces the basic HTML template that will be used an example
            in the following chapters

   .. container:: col-md-6 pl-0 pr-3 py-3 m-0

      .. container:: card px-0 h-100

         .. rst-class:: card-header h3

            .. rubric:: :ref:`Fluid templates <fluid-templates>`

         .. container:: card-body

            Explains how the build-in template engine "Fluid" can be used
            to generate the output of the HTML.

   .. container:: col-md-6 pl-0 pr-3 py-3 m-0

      .. container:: card px-0 h-100

         .. rst-class:: card-header h3

            .. rubric:: :ref:`TypoScript configuration <typoscript-configuration>`

         .. container:: card-body

            The configuration language TypoScript is used to tell TYPO3 how to
            output the content. It is also used to configure the Fluid templates.

-  :ref:`Sitemap`

.. toctree::
   :hidden:

   Preface/Index
   Introduction/Index
   DesignTemplate/Index
   FluidTemplates/Index
   TypoScriptConfiguration/Index
   ExtensionConfiguration/Index
   ExtensionInstallation/Index
   MainMenuCreation/Index
   ContentMapping/Index
   Summary/Index
   Sitemap/Index
   Targets
