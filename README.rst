#################
sphinx-quickstart
#################

`Sphinx`_ documentation template.

This is an alternative to Sphinx's ``sphinx-quickstart`` you can use with
`diecutter`_.


*****************************
Generate Sphinx documentation
*****************************

You can generate the files with `diecutter`_'s online web service.

With your browser
=================

Fill up the form at https://diecutter.alwaysdata.net/rawgithub/diecutter/sphinx-quickstart/index.html

With curl
=========

.. code:: sh

   curl -X POST https://diecutter.alwaysdata.net/github/diecutter/sphinx-quickstart/master/template/docs -d 'project_name=myproject' > template.tar.gz

With wget
=========

.. code:: sh

   wget -O template.tar.gz --post-data 'project_name=myproject' https://diecutter.alwaysdata.net/github/diecutter/sphinx-quickstart/master/template/docs


.. target-notes::

.. _`Sphinx`: http://sphinx-doc.org/
.. _`diecutter`: http://diecutter.io
