# ansible-zeromq

[ZeroMQ](http://zeromq.org/) - Low-level networking library for building connected software.

[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

Description
-----------
ZeroMQ \zero-em-queue\, \ØMQ\:
 Ø  Connect your code in any language, on any platform.
 Ø  Carries messages across inproc, IPC, TCP, TIPC, multicast.
 Ø  Smart patterns like pub-sub, push-pull, and router-dealer.
 Ø  High-speed asynchronous I/O engines, in a tiny library.

Tunables
--------
* None

Dependencies
------------
* [telusdigital.apt-repository](https://github.com/telusdigital/ansible-apt-repository/)

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: telusdigital.zeromq

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* [Chris Olstrom](https://colstrom.github.io/) | [e-mail](mailto:chris@olstrom.com) | [Twitter](https://twitter.com/ChrisOlstrom)
