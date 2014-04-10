ONCE - ensures given commands are running one at a time
=======================================================
This script ensures the command passed to it as an argument is only running once. It does this by creating a lock file before the command is run and deleting it afterwards. To provide for commands dying, lock files expire after 3 hours.

Usage
-----

    ./once some-command --with --flags and arguments

License
-------
[![Public Domain](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

