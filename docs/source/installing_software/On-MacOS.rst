

.. raw:: html

   <!-- START doctoc generated TOC please keep comment here to allow auto update -->
   <!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->





* `Atom & Sync Settings <#atom--sync-settings>`_
* `Git <#git>`_
* `Anaconda & Python <#anaconda--python>`_
* `\ ``pip`` Packages <#pip-packages>`_


.. raw:: html

   <!-- END doctoc generated TOC please keep comment here to allow auto update -->



Atom & Sync Settings
====================


#. Download `Atom <https://atom.io/>`_\ , extract the zipped file, then drag the Atom application to your Applications folder. Next, open up Atom.
#. Open Atom settings by going to File > Settings (or Control + Comma).
#. Go to Install and search for ``sync-settings``. Click on the blue Install button in the ``sync-settings`` box.
#. Once it's done installing, click on the Settings button in the ``sync-settings`` box.
#. Create a new `Github personal access token <https://github.com/settings/tokens/new>`_. You may set the name to anything you'd like, but we recommend that you call it something descriptive, like "aguaclara-atom-configuration".
#. Check the "\ **gist**\ : Create gists" permission, then click Generate Token. Copy the generated token.
#. In the Atom ``sync-settings`` settings, paste your generated token in Personal Access Token.
#. Set the Gist Id to ``8cb1fed2721e41873e9bcb315c804579``.

   * This synchronizes your Atom settings and plug-ins with the required `AguaClara Atom configuration <https://gist.github.com/ethan92429/8cb1fed2721e41873e9bcb315c804579>`_.

#. Restart Atom. ``sync-settings`` will do its job in the background. You can check on its progress in File > Settings > Packages.

   * If you get a dialog box saying that ``sync-settings`` is out of date, click "Restore".

Git
===


#. Open **Terminal** and enter the following command:

   * ``git --version``

#. If you don't alread have Git, Xcode will prompt you to install it. Follow the prompts to install Git.
#. Open **Terminal** and un the two following commands with your name and Cornell email, carefully observing spaces and punctuation:

   * ``git config --global user.name "Firstname Lastname"``
   * ``git config --global user.email "NetID@cornell.edu"``

     * **\ *The quotation marks are important!*\ ** For example, the command should say something like ``git config --global user.name "Monroe Weber-Shirk"``.

Anaconda & Python
=================


#. Download the `Anaconda installer <https://www.anaconda.com/download/>`_ and double-click it to begin installation.
#. When the installer displays Advanced Options, select "Add Anaconda to my PATH environment variable".

   * Aside from this, you can just click "Next" through the entire installation.

``pip`` Packages
====================


#. Open **Terminal**\ , as you did when `installing Git <https://github.com/AguaClara/aguaclara_tutorial/wiki/Installing-on-Windows#git>`_.
#. Run the following command, carefully observing spaces and punctuation:

   * ``pip install aguaclara_research aide_design --user``

**Now, you're ready to get the `Interactive Tutorials <https://github.com/AguaClara/aguaclara_tutorial/wiki/Interactive-Tutorials>`_.**
