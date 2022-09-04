GitHub Downloads Count
======================

This script shows the download count of Public GitHub repositories.

In order to get the downloads count of all GitHub repositories of a specific user, you need to execute:

    python3 gdc github-username

You can specify a single project:

    python3 gdc github-username github-projectname

Example:

    python3 gdc rethinkdb

giving the output:

    rethinkdb-1.7.0.dmg: 454 downloads
    rethinkdb-1.7.0.i686.rpm: 449 downloads
    rethinkdb-1.7.0.x86_64.rpm: 450 downloads
    rethinkdb-1.6.1.dmg: 455 downloads
    
If you need to run python scripts on Windows, see [here](http://pythoncentral.io/execute-python-script-file-shell/ "How to Run a Python Script via a File or the Shell").
