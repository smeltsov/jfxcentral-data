# autumo UI

autumo UI is a rapid Java FX development framework.

## Features

- HTML views
- Provides a classic MVC structure
- Creates log-files within a proper application data directory structure with
[SLF4J](https://www.slf4j.org/) and [log4j2](https://logging.apache.org/log4j/2.x/) in every OS
- Installer component for creating application installers with several steps
(e.g. license agreement, basic setting, etc.); steps are configurable
- Registration view and application component for seamless integration with
the registration module
- Check for product update view that can be configured with simple online XML
files on any public web-server
- Full application configuration handling for macOS, Windows and Linux/UNIX
- Includes the autumo base library [autumo-commons](https://products.autumo.ch/javadoc/autumo-commons/index.html) with many features and
ready-to-use components (Console app framework/tools, caching, sms- and
phone-call-API, configuration & database manager, logging, mailing and many
utilities)
- Developer guide included
- ...and much more to easily code a Java FX application with little code.

## Purchase (with or w/o support), Download & Demo
Go [here](https://products.autumo.ch/modules/overview#at_ui).

## Quickstart (after Download)

- Make sure to reference the libraries in the `lib`-directory within your project
or install them with the `maven-install.sh|bat`-script to your local maven-repository.
- Subclass `ch.autumo.ui.fx.BaseApp`.
- Read Java API documentation for this module [here](https://products.autumo.ch/javadoc/autumo-ui/index.html) and [here](https://products.autumo.ch/javadoc/autumo-commons/index.html).
- See directory `etc` for further information and developer guide.
