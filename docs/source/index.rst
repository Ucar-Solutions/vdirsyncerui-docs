Introduction!
===================================

**vdirsyncer UI** is a Nextcloud App for managing `vdirsyncer <https://github.com/pimutils/vdirsyncer>`_ storages and collections which are going to synchronise bidirectionally.
vdirsyncer UI stores the information about storages, collections and user credentials into Nextcloud in order to schedule the sync with Nextcloud cron.

.. note::

   This project is under active development.

.. warning::
    vdirsyncer UI stores your credentials in plain text. Your credentials are stored in vdirsyncer config files under apps/vdirsyncerui/data and in the database.
    If your instance is not used by you exclusively, please make your users clear that there credentials are saved in plain text and that everyone with access to the
    file system and/or database will see them.
    As vdirsyncer UI is under active development as well as technical requirements by vdirsyncer, we decided to move forward in this way. We will definetly fix
    this in the future.

.. toctree::

   Requirements
   vdirsyncer UI
