.. The contents of this file are included in multiple topics.
.. This file describes a command or a sub-command for opscode-analytics-ctl.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


The ``uninstall`` subcommand is used to remove the |chef analytics| application, but without removing any of the data. This subcommand will shut down all services (including the ``runit`` process supervisor).

This subcommand has the following syntax:

.. code-block:: bash

   $ opscode-analytics-ctl uninstall

.. note:: To revert the ``uninstall`` subcommand, run the ``reconfigure`` subcommand (because the ``start`` subcommand is disabled by the ``uninstall`` command).





