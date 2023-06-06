# IWXXM Modelling

IWXXM (ICAO Meteorological Information Exchange Model) describes representations of aviation weather information as well as containers of ordered representations for exchange especially over the System Wide Information Management (SWIM) environment. The model is designed using the Unified Modelling Language (UML) with Sparx Enterprise Architect (EA) and transformed into a GML Application Schema through a generator in EA.

# A New Approach

IWXXM-SX is a trimmed down version of IWXXM which has removed all legacy packages and related components.  It allows us to have a better view of what has to be developed for representation of meteorological information to support production, exchange and consumption in the future SWIM environment.  It is experimental in nature and not intended to be used separately; instead, mature components will merge into the master branch of IWXXM for publication and implementation.

# IWXXM-SX Modelling

This repository contains resources for modeling IWXXM-SX, transforming it into XML/GML schemas, and collating Schematron rules defined in the model. It also allows the development of extensions to IWXXM features to further enhance its capability to exchange weather and related information.

# See Also

[IWXXM-SX XML/GML schemas and schematrons on GitHub](https://github.com/blchoy/iwxxm-sx)