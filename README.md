Getting Started
---------------

To get started with Android CuBox-i ROM, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the CuBox-i trees, use a command like this:

    repo init -u git://github.com/cubox-i/android.git -b <branch>

    latest OmniROM branch is [omni-4.4]

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>
     source build/envsetup.sh
     brunch cuboxi4pro


ps: may will be necessary to run the brunch command again
    due to bootloader build process

If you need more information or a more detailed guide, click [here to see our forum.](http://www.solid-run.com/community/)

Our official IRC Channels are hosted on Freenode:

[#cubox - USERS](http://webchat.freenode.net/?channels=cubox/)

[#cubox-devel - DEVELOPERS](http://webchat.freenode.net/?channels=cubox-devel/)

