.. figure:: https://galaxyproject.org/images/galaxy-logos/galaxy_project_logo.jpg
   :alt: Galaxy Logo

The latest information about Galaxy can be found on the `Galaxy Community Hub <https://galaxyproject.org/>`__.

Community support is available at `Galaxy Help <https://help.galaxyproject.org/>`__.

.. image:: https://img.shields.io/badge/chat-gitter-blue.svg
    :target: https://gitter.im/galaxyproject/Lobby
    :alt: Chat on gitter

.. image:: https://img.shields.io/badge/chat-irc.freenode.net%23galaxyproject-blue.svg
    :target: https://webchat.freenode.net/?channels=galaxyproject
    :alt: Chat on irc

.. image:: https://img.shields.io/badge/release-documentation-blue.svg
    :target: https://docs.galaxyproject.org/en/master/
    :alt: Release Documentation

.. image:: https://travis-ci.org/galaxyproject/galaxy.svg?branch=dev
    :target: https://travis-ci.org/galaxyproject/galaxy
    :alt: Inspect the test results

Galaxy Quickstart
=================

Galaxy requires Python 3.9 or higher. To check your Python version, run:

.. code:: console

    $ python -V
    Python 3.9.21

Start Galaxy:

.. code:: console

    $ sh run.sh

Once Galaxy completes startup, you should be able to view Galaxy in your
browser at: http://localhost:8080

For more installation details please see: https://getgalaxy.org/

Documentation is available at: https://docs.galaxyproject.org/

Tutorials on how to use Galaxy, perform scientific analyses with it, develop Galaxy and its tools, and admin a Galaxy server are at: https://training.galaxyproject.org/

Tools
=====

Tools can be either installed from the Tool Shed or added manually.
For details please see the `tutorial <https://galaxyproject.org/admin/tools/add-tool-from-toolshed-tutorial/>`__.
Note that not all dependencies for the tools provided in the
``tool_conf.xml.sample`` are included. To install them please visit
"Manage dependencies" in the admin interface.

Issues and Galaxy Development
=============================

Please see `CONTRIBUTING.md <CONTRIBUTING.md>`_ .


Plain Table
=============================

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+




Simple Table

=============================

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======



参照 https://sphinx-doc.cn/en/master/usage/restructuredtext/basics.html#hyperlinks 来试一下基础的语法的解析效果；

=================
行内标记
=================

*text* 表示强调（斜体），
**text** 表示强烈强调（粗体），以及反引号：``text`` 表示代码示例。


=================
列表
=================
* This is a bulleted list.
* It has two items, the second
  item uses two lines.


=================
文字块
=================
This is a normal text paragraph. The next paragraph is a code sample::

  It is not processed in any way, except
  that the indentation is removed.

  It can span multiple lines.

This is a normal text paragraph again.