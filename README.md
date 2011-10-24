# fabfile-redis

## Overview

Fabric recipe to install Redis.


## Requirements

* Fabric

You may also need to install other dependencies to satisfy requirements of Kyoto Tycoon. (such like Tcl8.5)


## Operations

Install required packages.

  % pip install -r packages.txt


And then try to "setup" to build and upload binaries.

  % fab -H localhost setup


## Known problems

* you must setup an account "deploy" on target host first.
* source host and target host should have binary compatibility.
