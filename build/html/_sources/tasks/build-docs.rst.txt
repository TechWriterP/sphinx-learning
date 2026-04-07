Build the documentation
=======================

Use this task to generate the HTML output for the site.

Before you begin
----------------

Make sure the virtual environment is activated.

Procedure
---------

#. Open PowerShell in the project folder.
#. Run ``.\make.bat html``.
#. Open ``build\html\index.html`` in a browser.

Result
------

The updated HTML site is generated in the ``build\html`` folder.


Example command
---------------

.. code-block:: powershell

   .\make.bat html

.. image:: /_static/images/my-image.png
   :alt: My practice image
   :width: 600px
   :align: center

.. figure:: /_static/images/my-image.png
   :alt: My practice image
   :width: 600px
   :align: center

   Figure 1. Example image in a Sphinx page.

Simple table example
--------------------

==============  =============================
Command         Purpose
==============  =============================
make.bat html   Build the HTML output
make.bat clean  Remove generated build files
==============  =============================

Grid table example
------------------

+------------------+----------------------------------+
| Command          | Purpose                          |
+==================+==================================+
| ``.\make.bat     | Build the HTML output.           |
| html``           |                                  |
+------------------+----------------------------------+
| ``.\make.bat     | Remove generated build files.    |
| clean``          |                                  |
+------------------+----------------------------------+
| ``sphinx-build   | Build HTML by calling            |
| -b html source   | ``sphinx-build`` directly.       |
| build\html``     |                                  |
+------------------+----------------------------------+
