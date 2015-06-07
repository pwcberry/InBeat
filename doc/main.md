# InBeat - documentation 

## Installation

* [Local and development installation (Virtual Box + Vagrant)](./installation.md)
* [Production installation (Chef)](./installation.md)
* [Manual installation](./installation.md)

## Tutorials

* [Smart TV Use Case](./tutorial-smarttv.md)

## Settings

All parameters can be set by edditing the configuration file: config.js (/inbeat/config.js). The recommended option is to edit only the global configuration file.  There is a set of specific configuration files for each InBeat module too (/inbeat/{module}/config.js). Those files inherit from global one and can overwite specific propertes if needed. 