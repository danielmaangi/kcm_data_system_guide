

Access
###################

At any given time, you can either be:

* `New user`_ or
* `Existing user`_

New user
****************
To get a new user on board, please submit a request to *info@globalfundkcm.or.ke* with 
title "KCM Data System User Account" for account creation. Provide at least the first and last name
and email address.

Existing user
==============
1.	Open your web browser and navigate to this URL: https://kcmdashboard.org/
2. Enter your *username* and *password* in the login fields
3.	Click the Login button to access ODS. 

**Note**: If your username and password are correct, you will be successfully logged into KODS.
Otherwise click on **Forgot Password** and follow the prompts.

.. image:: images/login.png
 :width: 600

Install Sphinx
****************

To build your document in HTML (or other formats) on your computer, you must
install Sphinx.

See :xref:`Sphinx Overview` for background reading. Then follow the steps below.

#. If you are using Windows, you might need to :xref:`Python Install`.

   Depending on your Windows setup, after installation you might need to manually add the Python directory to your path. Try the :xref:`Python Windows Install` for help.

   If you are using a Mac, it's probably installed.

#. :xref:`PIP Install`.

   Depending on your Windows setup, after installation you might need to manually add the PIP directory to your path.

#. Use PIP to install Sphinx. On the command line, enter::

   $ pip install Sphinx

.. note:: If you are using Windows, this might be a frustrating task. If you get stuck, share the error messages and ask for help.

You should now be able to create a Sphinx project. See :xref:`First Steps with Sphinx`.

Verify Sphinx Setup
**********************

You can use the :xref:`Get Started Sphinx Repo` to verify that Sphinx is set
up. You can also use it as the start of a new project.

#. Make a fork of the repository and check it out on your computer.

#. Open a command prompt and change directories to the ``get_started_sphinx``
   directory.

#. Run the command ``make html``. Check if there are warnings or errors in
   the command window.

#. Check for the HTML output in the ``get_started_sphinx/build/html`` directory.

#. Open the file ``index.html``.

   The page should look like the following image.

   .. image:: images/get_started_sphinx.png
     :width: 600

If you the HTML is generated and there are no warnings or errors in the
command prompt, Sphinx is set up correctly.

Sphinx Videos
=============

These videos are very long and detailed. But they are great resources if
you need to complete real projects in Sphinx. 

.. youtube:: hM4I58TA72g

.. youtube:: QNHM7q2hLh8


Learn RST
*************

To learn RST syntax, see the :xref:`RST Primer`. Then see the following video.

.. youtube:: hM4I58TA72g

You can experiment with RST with the :xref:`Online RST Writer`

.. note:: Indentation is important in RST. Lots of problems are caused by inconsistent indentation. The only way to learn is to practice and see the results.
