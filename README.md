Phing Drush
===========

## Overview

A collection of Drush targets for Phing.

## Installation

This project can be checked out with Composer.

```
"require": {
    "doghouseagency/phing-drush": "*"
}
```

If you are already running a Phing build in an existing project why not
include these tasks as well with the following line in your build.xml:

```
<import file="vendor/doghouseagency/phing-drush/build.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.cache.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.cron.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.database.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.download.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.features.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.files.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.install.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.maintenance.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.user.xml" optional="true" />
<import file="vendor/doghouseagency/phing-drush/build.watchdog.xml" optional="true" />
```

We also provide some template files that should be added (and updated)
to the root of the project. These files are:

* example.aliases.drushrc.php

## Usage

To get a list of tasks.

```
phing -l
```
