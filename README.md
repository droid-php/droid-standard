droid-standard
==============

[Droid](https://github.com/droid-php/droid) meta package, including a set of standard plugins.

This repository does not contain any code, it just includes a `composer.json` that depends on `droid/droid` and a set of standard plugins.

You can choose to depend on `droid/droid-standard` to get all droid and all standard plugins in one go, or be more specific, and depend on `droid/droid`, and add your preferred plugins manually, by depending on `droid/droid-composer` etc.

Check the included composer.json file to see a current list of all included plugins.

## Rebuilding droid.phar

This repository is also used to build the standard droid.phar file. To rebuild it, run:

    composer install
    vendor/bin/box build


