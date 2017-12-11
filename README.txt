COPYRIGHT AND LICENSE
=====================
Apache Version 2.0 License (see LICENSE)
Copyright (c) 2017 Arthur Naseef

OVERVIEW
========
This project contains a minimal Maven multi-module project for an application that uses docker to
containerize and run the application during built-in integration testing.

MODULES
=======

    app - contains source code for an application, packaged as an executable jar.
    integration-test - contains the maven configuration for creating and running the docker image.
