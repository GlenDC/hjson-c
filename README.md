# hjon-c

Hjson, the Human JSON. A data format that caters to humans and helps reduce the errors they make.

For details and syntax see http://laktak.github.io/hjson.

hjson-c is a subset of [jansson](https://github.com/akheron/jansson) and licensed under the [MIT license](http://www.opensource.org/licenses/mit-license.php), see LICENSE in the source distribution for details.

Its main features and design principles are:

+ Simple and intuitive API and data model
+ Comprehensive documentation
+ No dependencies on other libraries
+ Full Unicode support (UTF-8)
+ Extensive test suite

## Library is still under construction

Right now the Library is still under development and therefore it is unsuitable for end use. Please be patient and start the project to get regular updates. As we're in early development it is pretty hard for me to coordinate and get other people involved in the development. Once the lib reaches a decent state this will change. If however, you feel like you absolutely would get involved already, feel free to [let me know](mailto:contact@glendc.com).

### TO-DO List

* [-] Get familiar with the JANSSON JSON lib and documentation;
* [-] Convert to the correct naming conventions;
* [-] Modify the lib to handle the hjson subset syntax;
* [-] Make the tests reflect the code changes;
* [-] Synchronise the documentation with the code base;
* [-] Introduce version 1.0.0 of the hjson-c library;

## From the Commandline

A commandline tool to convert from/to Hjson is available at https://github.com/laktak/hjson-js.

## Compilation and Installation

If you obtained a source tarball, just use the standard autotools
commands:

   ```
   $ ./configure
   $ make
   $ make install
   ```

To run the test suite, invoke:

   ```
   $ make check
   ```

If the source has been checked out from a Git repository, the
./configure script has to be generated first. The easiest way is to
use autoreconf:

   ```
   $ autoreconf -i
   ```

## Documentation

Prebuilt HTML documentation is available at
http://www.digip.org/jansson/doc/.

The documentation source is in the ``doc/`` subdirectory. To generate
HTML documentation, invoke:

   ```
   $ make html
   ```

Then, point your browser to ``doc/_build/html/index.html``. [Sphinx](http://sphinx.pocoo.org/)
1.0 or newer is required to generate the documentation.
