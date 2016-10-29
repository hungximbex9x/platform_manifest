Android Open Kang Project (Zenfone 5)
=====================================

Getting Started
---------------

To get started with Android/CyanogenMod, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/hungximbex9x/platform_manifest.git -b mm

Then to sync up:

    repo sync -c -j16

Patching
--------

Use the files from the `Patch` repository on BitBucket and patch the respective folders.

Search on how to apply a patch file.

Building
--------

This manifest will already come with the Zenfone 5 device files,
so all you need to do is build it.

    . build/envsetup.sh

    lunch aokp_T00F-user

    mka rainbowfarts -j16

Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) or [Android Docs](https://source.android.com/source/building.html) for more building instructions.

Submitting Issues
-----------------

To submit an issue, please go to [Create issue](https://bitbucket.org/zf5/android/issues/new) and explain your issue.
Don't forget to include a logcat.
