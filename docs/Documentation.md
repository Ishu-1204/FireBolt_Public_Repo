
# FCA: Documentation

Welcome to the FCA (Firebolt Certification Application) documentation. Explore FCA's diverse capabilities, from configuration options to executing tests, validations, and more. This landing page offers concise overviews of each functionality offered, with links to more detailed documentation for comprehensive guidance.

The basic idea of FCA is:

- Launch FCA on an integrated device
- Use FCA to make Firebolt SDK calls on the device
- Validate the SDK responses
  
## Table of Contents

  - [Graphical User Interface (GUI)](#graphical-user-interface)
  - [Configuration Options](#configuration-options)
  - [Test Executions](#test-executions)
  - [Validations](#validations)
  - [Reporting](#reporting)
  - [Plugins](#plugins)

## Graphical User Interface

When you launch the Firebolt Certification Application (FCA) GUI, you gain access to a range of features and functionalities designed to facilitate Firebolt SDK testing and validation on integrated devices. For more details about the GUI please read the [Graphical User Interface documentation](GUI.md).

## Configuration Options

To learn more about configuration options see the [configuration documentation](./Configurations.md).

## Test Executions

To learn more about how to execute tests please see the [execution documentation](./Execution.md).

## Validations

To learn more about validation options see the [validation documentation](./Validations.md).

## Reporting

If you are interested in taking advantage of the built-in reporting please see the [reporting documentation](./Reporting.md).

## Plugins
Plugins are powerful tools that enable custom functionality to be added to FCA. They are optional. They are available for those who wish to extend or override FCA's capabilities. All plugins are located in the `/plugins` directory and use webpack to be added to the application during build time. Full overview of the Plugins functionalities can be found [here](plugins/Plugins.md).