AOSP (barrmy)
===========

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u https://github.com/barrmy/android.git -b master

Then to sync up:

    repo sync

Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.com/) for building instructions.

For more information on this Github Organization and how it is structured, 
please [read the wiki article](http://wiki.cyanogenmod.com/index.php/Github_Organization)

Building
--------

Once you are done with syncing, use a command like this for building:

. build/envsetup.sh
lunch

Extracting vendor files
-----------------------

To extract vendor files from the device go to the google Nexus webpage

