Simpletester
=================

Simpletest's Testing UI allows running an entire test class, but not individual
tests (methods), whereas this can be done via command line. This module modifies
Simpletest UI to choose and run individual tests methods.

For example, run `testNodeAdd` and/or `testNode` from the
`AdminBarDynamicLinksTestCase` Class in Admin Bar tests.

Installation and Usage:
---------------
- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules)
- Once enabled, a new link will be available in the Simpletest UI list of tests
at `admin/config/development/testing` next to each test class in a test group.
- Click this `Choose tests` link to select one or more test methods to run.

License
---------------

This project is GPL v2 software. See the LICENSE.txt file in this directory
for complete text.

Current Maintainers
---------------

- [Docwilmot](https://github.com/docwilmot)
