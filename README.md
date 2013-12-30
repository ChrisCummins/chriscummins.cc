# DEPRECATED REPOSITORY

This repository contains the *old* source code for
http://chriscummins.cc. Note that this has moved to a shiny [new
repository](https://github.com/ChrisCummins/chriscummins.github.io/),
and this old code has been [merged
in](https://github.com/ChrisCummins/chriscummins.github.io/commit/2e352b94e0f7a166b2a31401e7e87819ef758a4f). This
repository is pending deletion.

Any source code I've written is released under the MIT license (see
[COPYING](COPYING)). Any third-party code is distributed under the terms of
their license.

## Building the website

The website can be built in a GNU/Linux environment using the standard GNU
Autotools procedure:

```sh
$ ./autogen.sh
$ ./configure
$ make all
```

See `./configure --help` for a list of configuration options for building the
website.

### Requirements
* [Autoconf](http://www.gnu.org/software/autoconf/)
* [Automake](http://www.gnu.org/software/automake/)
* [Java](http://www.java.com/en/)
* [Node.js](http://nodejs.org/)
* [Less](http://lesscss.org/)

## Hosting the website

The website can be deployed on a LAMP stack, by exporting the contents of the
`/build/www` directory.

### Requirements
* [Apache](http://www.apache.org/)
* [MySQL](http://www.mysql.com/)
* [PHP](http://php.net/)
