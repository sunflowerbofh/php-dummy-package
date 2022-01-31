# php-package

Template for debian php-\* packages

This is a framework for php packages built for debian.
Adopt changelog, control, copyright and install (eventually also rules).

You will probably need the pkg-php-tools, as well as composer and phpab.

When everything is done you can build the package as usual with 'dpkg-buildpackage (-k<yourkey>).
Attention: Once you want to build it a second time you have to remove src/autoload.php first.

For more information read /usr/share/doc/pkg-php-tools/README.Composer.
