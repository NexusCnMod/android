Getting Started
---------------

To get started with Nexus ROM, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the OMNIROM trees, use a command like this:

    repo init -u git://github.com/NexusCnMod/android.git -b <branch>

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; brunch <device_name>