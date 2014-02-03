Using a Pre-created Virtual Machine
===================================

.. role:: usertype
    :class: usertype

Some users prefer to create their own Virtual Machines (VM)s ahead of time
instead of using Vagrant to create the VM on-demand or for installing on
bare-metal.

This requires more manual steps to get started and will mostly replicate the
steps that Vagrant would have done for you automatically.

Requirements
------------

 * An Ubuntu VM (Ubuntu 12.04 LTS tested)
 * Login information for a user with sudo access (you are on your own to do the
   substitution if you login as root)
 * Familiarity with Linux

Install
-------

The script can be downloaded and executed from the git repository:

.. parsed-literal::

    ~$ :usertype:`curl https://raw.github.com/OSEHRA/VistA/master/Scripts/Install/Ubuntu/autoInstaller.sh | bash`

This will download and execute the autoInstaller script using the defaults
embedded in the script. A full explanation of the command-line options of
autoInstaller.sh is available.

.. _`Amazon Web Services`: http://aws.amazon.com/
.. _`autoInstaller.sh`: autoInstaller.rst
.. _Vagrant: Vagrant.rst